pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the code using Maven'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Running tests using JUnit'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Analysing code using SonarQube'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Scanning for vulnerabilities using OWASP'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to a staging AWS EC2 instance'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Testing on staging using Postman'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploying to a production AWS EC2 instance'
            }
        }
    }
}
