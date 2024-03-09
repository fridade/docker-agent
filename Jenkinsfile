pipeline {
    agent {
        docker {
            image 'maven:3.8.1-adoptopenjdk-11'
        }
    }

    stages {
        stage('build') {
            steps {
                echo 'Hello World from build stage'
            }
        }

        stage('test') {
            steps {
                echo 'Hello World from test stage'
            }
        }

        stage('deploy') {
            steps {
                echo 'Hello World from deploy stage'
            }
        }
    }
}
