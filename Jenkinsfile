@Library("my-lib") _
pipeline{
    agent any
    stages{
        stage('Checkout'){
            steps{
                   git branch: 'main', url: 'https://github.com/Jaisharma2512/jenkins-trigger-test.git'
            }
        }
        stage('Hello'){
            steps{
                helloWorld()
            }
        }
    }
}