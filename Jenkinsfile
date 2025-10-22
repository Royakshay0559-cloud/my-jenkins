pipeline {
    agent any
    
        stage('Clone Repo') {
    steps {
        git 'https://github.com/Royakshay0559-cloud/my-jenkins.git'
    }
}
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy complete ✅'
            }
        }
    }
}
