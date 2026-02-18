pipeline {
    agent any
    environment {
        DEPLOY_DIR = "/var/www/site1"
    }
    stages {
        stage('Deploy') {
            steps {
                sh '''
                rm -rf $DEPLOY_DIR/*
                cp -r * $DEPLOY_DIR/
                '''
            }
        }
    }
}
