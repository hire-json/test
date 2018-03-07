pipeline {
    agent { label 'master' }
    stages {
        stage('Test') {
            steps {
                sh 'cat test'
            }
        }
    }
    post {
        always {
            deleteDir()
        }
    }
}

