pipeline{
    agent any
    stages {
        stage('Make Directory'){
            steps {
                sh "mkdir ~/pipeline-tutorial-test"
            }
        }
        stage('Make Files'){
            steps{
                sh "touch ~/pipeline-tutorial-test/file1 ~/pipeline-tutorial-test/file2"
            }
        }
    }
}