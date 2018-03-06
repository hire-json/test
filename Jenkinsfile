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
        allways {
            deleteDir()
        }
    }
}

