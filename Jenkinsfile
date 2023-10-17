pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/nunidoron/ex8-pl.git'
                sh 'python main.py'
            }
        }
    }
}
