pipeline {
    agent any
    stages {
        stage('build da imagem docker'){
            steps{
                sh 'docker build -t latest'
            }
        }
        stage('Sleep para a preparação do build '){
            steps{
                sh 'sleep 10'
            }
    }
}
