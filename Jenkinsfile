pipeline{
    agent any

    stages{
        stage("Install NPM dependencies"){
            steps{
                sh 'npm install'
            }            
        }
        stage("Run Tests"){
            steps{
                sh 'npm test'
            }
        }
    }
}