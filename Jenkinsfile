      pipeline {
    agent any
stages {
   
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
                jacoco()
            }
        }
           stage('Building Docker Image') {
            steps {
                echo 'Building Docker Image'
            }
        }
    }
}

