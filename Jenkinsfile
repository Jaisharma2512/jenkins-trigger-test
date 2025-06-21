pipeline{
    agent any
    stages{
        stage('Checkout'){
            steps{
                   git branch: 'main', url: 'https://github.com/Jaisharma2512/jenkins-trigger-test.git'
            }
        }
        stage('Build'){
            steps{
                echo 'code has been pushed. hurray'
            }
        }
    }
}