pipeline{
    agent any
    stages{
        stage("Git CheckOut"){
            steps{
                git credentialsId: 'myCredentials', url: 'https://github.com/mhkumar631/NewSampleProject.git'
            }
        }
        stage("Build Stage"){
            steps{
                sh "ls -lrt"
            }
        }
    }
}
