pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                build 'SeleniumMaven'
            }
        }
        
        stage('test') {
            steps {
                echo 'Testing..'
            }
        }
        
        stage('deploy') {
            steps {
                echo 'Deploying..'
            }
        }
    }
    post {
        always {
            echo 'pipeline done'
        }
    }
}
