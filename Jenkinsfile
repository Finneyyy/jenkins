pipeline{
    agent any
    stages {
        stage('Make Directory'){
            steps {
                sh "mkdir ~/pipeline-tutorial-test"
                sh "pwd && ls -la"
            }
        }
        stage('Make Files'){
            steps{
                sh "touch ~/pipeline-tutorial-test/file1 ~/pipeline-tutorial-test/file2"
            }
        }
    }
}