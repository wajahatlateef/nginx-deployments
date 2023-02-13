pipeline{
    agent any
    stages{
        stage('applying kubernetes manifest'){
            steps{
                sh "kubectl apply -f nginx.yaml"
            }
        }
    }
}