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
                sh 'cat /etc/os-release/'
            }
        }
        stage('DockerBuild') {
            steps{
                sh 'docker build -t httpd'
                sh 'docker images'
            }
        }
    }
}