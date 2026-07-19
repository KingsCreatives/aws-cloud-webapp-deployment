pipeline {
    agent any

    environment {
        WEB_DIR = '/var/www/html'
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Deploy to EC2') {
            steps {
                sh """
                    cd ${WEB_DIR}
                    sudo git pull origin main
                    sudo cp -r src/* . 2>/dev/null || true
                    sudo rm -rf src
                    sudo systemctl restart httpd
                """
            }
        }
    }

    post {
        success {
            echo '✅ Deployment successful!'
        }
        failure {
            echo '❌ Deployment failed. Check logs.'
        }
    }
}
