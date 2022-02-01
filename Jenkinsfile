pipeline {
    agent any

    stages {
        stage('Init') {
            steps {
                echo 'Initializing'
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
                echo 'Releasig'
            }
        }
    }
    post {
        always{
            echo 'post always'
        }
        failure{
            echo 'post failure'
        }
    }
}
