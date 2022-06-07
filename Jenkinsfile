      pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/Venkatareddyjaddu/Olx-User-Microservice.git'
            }
        }
            stage('Compile') {
            steps {
                bat 'mvn clean compile'
            }
        }
        stage('Run') {
            steps {
                bat 'mvn package'
            }
        }
          stage('Test Report Using jacoco') {
            steps {
                echo 'jacoco'
            }
        }
           stage('Building Docker Image') {
            steps {
                echo 'Building Docker Image'
            }
        }
    }
}

