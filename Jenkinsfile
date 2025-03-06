pipeline {

    agent any

    stages{
        stage('build') {
            steps{
                sh 'echo $BUILD_ID'
            }
        }
        stage('pwd command') {
            steps{
                sh 'pwd'
            }
        }
        stage('ls command') {
            steps{
                sh 'ls'
            }
        }
    }
}