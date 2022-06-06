      pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/mohammadazeez963/javaProject.git'
            }
        }
            stage('Compile') {
            steps {
                echo 'Compiling'
            }
        }
        stage('Run') {
            steps {
                echo 'Running'
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

