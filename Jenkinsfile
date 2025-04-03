pipeline {
    agent {
        label 'docker-jenkin'
    }
    stages {
        stage('Saludo') {
            steps {
                sh 'echo "Pipeline que ejecuta dentro del dock"'
            }
        }
    }
    
    post {
        success {
                echo "Jala"
           }
        }
}
