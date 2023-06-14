pipeline {
    agent any

    stages {
        stage('Run test file') {
            steps {
                echo "Hi"
                sh "yum install python"
                sh "python test.py"
            }
        }
    }
}
