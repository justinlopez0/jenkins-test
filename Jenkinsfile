pipeline {
    agent any
    stages {
        stage('Composer Install') {
            steps {
                sh 'composer install'
            }
        }
        stage('Unit Tests') {
            steps {
                sh 'vendor/bin/phpunit'
	        sh 'ls'
            }
        }
    }
}
