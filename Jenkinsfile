
pipeline {
    agent any
    stages {
        stage ('Init'){
            steps {
                script {
                    currentBuild.description = "test2"
                }
                sh "touch 2"
                sh "touch 12"
                archiveArtifacts artifacts: "2", "12"
            }
        }
    }
}