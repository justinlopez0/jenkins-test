pipeline {
    agent any
    stages {
        stage('Composer Install') {
            steps {
                cp jenkins.env .env
                sh 'composer install --ignore-platform-reqs'
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
