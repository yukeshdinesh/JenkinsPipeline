pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building the project'
          }
        }

        stage('Test') {
          steps {
            echo 'Testing the app'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying the app in staging'
      }
    }

  }
}