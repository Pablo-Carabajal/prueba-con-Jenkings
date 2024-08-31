pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Compilar el programa Java
                sh 'javac HolaMundo.java'
            }
        }
        stage('Test') {
            steps {
                // Ejecutar el programa y verificar la salida
                sh 'java HolaMundo'
            }
        }
    }
}
