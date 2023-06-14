pipeline {
    agent any

    stages {
        stage('Run test file') {
            steps {
                echo "Hi"
                sh "python --version"
                sh "python test.py"
            }
        }
    }
}
