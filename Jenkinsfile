pipeline {

    agent {
        docker {
            image 'node:16-alpine3.14'
            args '-p 3000:3000 -p 5000:5000'
            args '-u 0:0'

        }
    }

    environment {
        project_name = 'uat/authentication'
        outputPath = 'authentication'
    }

    stages {

        stage('Install') {
            steps {
                sh 'pwd'

            }
        }

        stage('Build') {
            steps {
                sh 'pwd'

            }
        }

    }
}
