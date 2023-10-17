properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'python main.py'
            }
        }
        stage('Bye') {
            steps {
                sh 'python main.py'
            }
        }
    }
}
