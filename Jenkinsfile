pipeline {
    agent any

    stages {
        stage('clean') {
            steps {
                echo 'cleaning workspa
                cleanWs()
            }
        }

        stage('build') {
            steps {
                echo 'building the application'
            }
        }

        stage('test') {
            steps {
                echo 'running test'
            }
        }

        stage('deploy') {
            steps {
                echo 'deploying to production'
            }
        }
    }
}
