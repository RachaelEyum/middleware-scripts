pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
                script{
            sh 'zip middlewasreScript-${BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md'   
            }
            }
        }
        
    }
}