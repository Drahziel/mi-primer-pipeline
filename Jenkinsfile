pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Drahziel/mi-primer-pipeline.git'
            }
        }

        stage('Build') {
            steps {
                echo '🏗️ Probando webhook CI/CD'
            }
        }

        stage('Test') {
            steps {
                echo '✅ Ejecutando tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Desplegando aplicación...'
            }
        }
    }
}




