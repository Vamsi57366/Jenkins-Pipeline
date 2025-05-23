pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the code using Maven'
            }
        }

        stage('Unit & Integration Tests') {
            steps {
                echo 'Running tests using JUnit and Mocha'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analyzing code quality using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Scanning for vulnerabilities with Snyk'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying staging environment using Docker'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running end-to-end tests on staging'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying to production using AWS CLI'
            }
        }
    }
}
