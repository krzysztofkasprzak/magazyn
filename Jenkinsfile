
pipeline {
    agent any
    stages {
        stage ('Init'){
            steps {
                script {
                    currentBuild.description = "test2"
                }
                sh "touch ${COMMIT}"
                sh "touch ${COMMIT}2"
                archiveArtifacts artifacts: "${COMMIT}", "${COMMIT}2"
            }
        }
    }
}