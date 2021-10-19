pipeline {
    agent any
    tools {nodejs "NodeJS16"}

    stages {
        stage('source') {
            steps {
                git 'https://https://github.com/akbar-alam/JenkinsWebHooks/
            }
        }
        stage('Build') {
            steps {
               cat 'Hello.txt'
            }
        }
        
        stage('Build') {
            steps {
               sh 'npm install'
            }
        }
    }
}
