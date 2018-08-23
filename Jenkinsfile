pipeline {
    agent any

    stages {
        staget('info') {
            steps {
                echo 'feature branch'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Building'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}
