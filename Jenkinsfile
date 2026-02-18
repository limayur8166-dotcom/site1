pipeline {
    agent any

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
