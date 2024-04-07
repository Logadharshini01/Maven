pipeline {
    agent any

    stages {
        stage('Build now') {
            steps {
                echo 'Build app first'
            }
        }
	stage('Test') {
            steps {
                echo 'test app second'
            }
        }
	stage('deploy') {
            steps {
                echo 'deploy app third'
            }
        }
    }
}
