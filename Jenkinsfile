pipeline {
    agent any
    stages {
        stage('BUILD') {
            steps {
                sh '''
                    #!/bin/bash
                    pwd
                    ls -lrt
                    sleep 5
                '''
            }
        }   
        
        stage('TEST-WINDOWS') {
            steps {
                sh """
                    #!/bin/bash
                    pwd
                    ls -lrt
                    sleep 5
                """
            }
        }   

        stage('TEST-LINUX') {
            steps {
                sh 'sleep 5'
            }
        }
        
        stage('DEPLOY') {
            steps {
                sh 'sleep 5'
            }
        }   
    }
}
