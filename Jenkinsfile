
pipeline {
    agent any
    stages {
        stage ('Init'){
            steps {
                script {
                    currentBuild.description = "test2"
                }
                sh "touch ${COMMIT}"
            }
        }
    }
}