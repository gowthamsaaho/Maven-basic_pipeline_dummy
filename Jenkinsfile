pipeline {
    agent any
    tools{
        jdk 'java17'
        maven 'maven3'
    }
    stages {
        stage('maven Build') {
            steps {
                echo 'mvn clean install'
            }
        }
    }
}


