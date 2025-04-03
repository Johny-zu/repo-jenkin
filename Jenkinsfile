pipeline {
    agent {
        label 'docker-jenkins' // Corregido el label
    }
    stages {
        stage('Saludo') {
            steps {
                echo "Iniciando el pipeline..."
                sh 'echo "Pipeline que ejecuta dentro del docker"' // Corregido el mensaje
            }
        }
    }
    
    post {
        success {
            echo "Pipeline ejecutado con éxito"
        }
        failure {
            echo "El pipeline falló"
        }
    }
}