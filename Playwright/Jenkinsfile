pipeline {
    agent{
        linux
    }
    options {
        buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '4', daysToKeepStr: '', numToKeepStr: '4')
        disableConcurrentBuilds()
    }
    stages{
        stage('hello') {
            steps{
                echo "hello"
            }
        }
    }
}
