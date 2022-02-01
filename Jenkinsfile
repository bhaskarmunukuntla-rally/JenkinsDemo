pipeline {
    agent any
    environment {
        VERSION = '0.0.1'
    }
    stages {
        stage('Init') {
            steps {
                echo 'Initializing'
            }
        }
     stage('Build') {
            steps {
                echo 'Building'
                echo "this is my ${VERSION}"
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
