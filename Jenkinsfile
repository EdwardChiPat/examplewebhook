#!groovy
pipeline {
    agent any
    stages {
        stage('Crear Archivo'){
            steps {
                sh 'touch archivo.txt'
            }
        }
        stage('Ingresando datos archivos') {
            
            steps {
                echo 'Ingresando datos archivo'
                sh 'echo hola > archivo.txt'
            }
        }
        stage('Enlisto'){
            steps {
                echo 'Unit Tests'
                sh 'ls'
            }
        }
    }
}
