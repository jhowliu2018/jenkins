pipeline {
    agent any

    stages {
        staget('info') {
            steps {
                echo 'feature branch testing typo...'
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
