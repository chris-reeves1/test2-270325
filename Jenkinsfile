pipeline{
    agent any
    stages{
        stage("make_directory"){
            steps{
                sh "mkdir ~/jenkins-test || true"
                }
            }
        stage("add a file"){
            steps{
                sh "touch ~/jenkins-test/file1"
            }
        }
    }
}

