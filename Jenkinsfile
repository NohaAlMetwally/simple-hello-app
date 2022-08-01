pipeline {
    agent any
    stages {
     
        stage('CD') {
            steps {
                script {
                      sh 'kubectl apply -Rf ./hello--app'
                }
            }
        }
    }

}
