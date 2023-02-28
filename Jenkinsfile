pipeline {
    agent any
    stages {
        stage('Unit Tests') {
            steps {
                sh 'vendor/bin/phpunit'
	        sh 'ls'
            }
        }
    }
}
