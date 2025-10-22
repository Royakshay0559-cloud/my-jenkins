pipeline {
    agent any

        stage('Clone Repo') {
    steps {
        git url: 'https://github.com/Royakshay0559/jenkins-demo.git', branch: 'main'
    
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

