pipeline {
    agent any

    tools {
        maven 'localMaven'
    }

    stages {
        stage ('Build') {
            sh 'mvn clean package'
        }
    }
}