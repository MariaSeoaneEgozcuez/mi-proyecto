pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                git 'https://github.com/tu-usuario/mi-proyecto.git'
                sh 'echo "Construyendo..."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Ejecutando pruebas..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Desplegando..."'
            }
        }
    }
}
