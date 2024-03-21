pipeline {
  agent any
  stages {
    stage('Plan ') {
      steps {
        echo 'I have a plan to work on CICD'
      }
    }

    stage('Code') {
      steps {
        echo 'I have a code to work on CICD'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'I have a build to work on CICD'
          }
        }

        stage('Test') {
          steps {
            echo 'I have a Test to work on CICD'
          }
        }

        stage('Release') {
          steps {
            echo 'I have a Release to work on CICD'
          }
        }

        stage('Deploy') {
          steps {
            echo 'I have a Deploy to work on CICD'
          }
        }

        stage('Operate') {
          steps {
            echo 'I have a Operate to work on CICD'
          }
        }

      }
    }

  }
}