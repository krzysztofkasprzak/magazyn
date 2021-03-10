
pipeline {
    agent any
    stages {
        stage ('Init'){
            steps {
                script {
                    currentBuild.description = "test2"
                }
                sh "touch 2.zip"
                sh "touch 12.zip"
                archiveArtifacts artifacts: "*.zip"
            }
        }
    }
}