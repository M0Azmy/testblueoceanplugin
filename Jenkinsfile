pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build completed'
      }
    }

    stage('Test1') {
      parallel {
        stage('Test1') {
          steps {
            echo 'running test 1'
          }
        }

        stage('test 2') {
          steps {
            echo 'running test 2'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployment '
      }
    }

  }
}