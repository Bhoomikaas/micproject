pipeline {
    agent {
        label 'slave'
    }
    stages {
        stage('server hostname') {
            steps {
                sh 'hostname'
            }
        }
        stage('server uptime') {
            steps {
                sh 'uptime'
            }
        }
        stage('server disk usage') {
            steps {
                sh 'df -h'
            }
        }
        stage('cpu details') {
            steps {
                sh 'lscpu'
            }
        }
        stage('Memory Usage') {
            steps {
                sh 'free -h'
            }
        }
        stage('Date') {
            steps {
                sh 'date'
            }
        }
    }
}

