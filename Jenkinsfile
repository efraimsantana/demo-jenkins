pipeline {
    agent none
    stages {
        stage('Build') { 
            agent any
            steps {
                echo sh(script: 'env|sort', returnStdout: true)
                sh 'echo "Build - Hello World"'
                sh 'echo ${BRANCH_NAME}'
            }
        }
        stage('Test') { 
            agent any
            steps {
                sh 'echo "Test - Hello World"'
            }
        }
        stage('Deploy') { 
            agent any
            steps {
                sh 'echo "Deploy - Hello World"'
            }
        }       
    }
}
