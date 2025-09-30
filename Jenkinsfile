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
                echo '🏗️ Compilando proyecto...'
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




