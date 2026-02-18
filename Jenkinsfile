pipeline {
    agent any

    environment {
        DEPLOY_DIR = "/var/www/site1"
    }

    stages {
        stage('Deploy') {
            steps {
                sh '''
                echo "Current directory:"
                pwd
                ls -la

                mkdir -p /var/www/site1
                cp -r * /var/www/site1/
                '''
            }
        }
    }
}
