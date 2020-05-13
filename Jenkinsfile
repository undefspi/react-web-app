pipeline{
    agent{ docker { image 'node:6.3' } }
    stages{
        stage("test"){
            sh 'echo hello world'
            sh 'npm --version'
        }
    }
}