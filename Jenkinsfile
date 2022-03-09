pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                build quietPeriod: 5, job: 'test_1'
            }
        }
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
         stage('Release') {
            steps {
                echo 'Releasing'
            }
        }
    }
}
