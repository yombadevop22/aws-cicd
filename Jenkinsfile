pipeline {

    agent any

    stages{
        stage('build') {
            steps{
                sh 'echo $BUILD_ID'
            }
        }
        stage('test') {
            steps{
                sh 'echo test'
            }
        }
        stage('deploy') {
            steps{
                sh 'docker -v'
            }
        }
    }
}