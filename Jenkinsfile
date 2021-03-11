
pipeline {
    agent any
    stages {
        stage ('Init'){
            steps {
                script {
                    currentBuild.description = "test2"
                }
                sh "mkdir test"
                sh "touch test/2.zip"
                sh "touch test/12.zip"
                sh "ls -a"
                archiveArtifacts artifacts: "test/*.zip"
            }
        }
    }
}