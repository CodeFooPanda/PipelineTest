pipeline {
    agent any

    stages {
        stage('Hello From GitHub') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build TestGit') {
            steps {
                echo 'Building TestGit'
                build quietPeriod: 5, job: 'TestGitJob'
            }
        }
    }
}
