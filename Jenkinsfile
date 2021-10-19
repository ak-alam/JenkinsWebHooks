pipeline {
    agent any
    tools {nodejs "NodeJS16"}

    stages {
        stage('source') {
            steps {
                git 'https://github.com/sd031/aws_codebuild_codedeploy_nodeJs_demo'
            }
        }
        stage('Build') {
            steps {
               sh 'npm install'
            }
        }
    }
}
