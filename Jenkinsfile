pipeline {
    agent any
    stages {
        stage('Clone Code') {
            steps {
                echo "Clonning the code"
            }
        }
        
        stage('Build code') {
            steps {
                echo "Building the code using docker"
            }
        
        }
        
        stage('Push to docker Hub') {
            steps {
                echo "Pushing the code to dockerhub"
            }
        }
        
        stage('Deploy to alan inspiron') {
            steps {
                echo "Deploying the code to alan inspiron"
            }
        }
        
    }
}
