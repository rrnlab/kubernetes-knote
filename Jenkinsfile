pipeline {

    agent any

    stages{

        stage('checkout'){

            steps{
                git 'https://github.com/rrnlab/kubernetes-knote.git'
            }
        stage('unit test'){

            steps{
                sh 'mvn test'
            }
        }
        }
    }
}