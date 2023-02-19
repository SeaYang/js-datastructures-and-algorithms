pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "yyds"'
          }
        }

        stage('stage1-1') {
          steps {
            sh 'echo "stage1-1"'
          }
        }

        stage('stage1-2') {
          steps {
            sh 'echo "stage1-2"'
          }
        }

      }
    }

    stage('stage2') {
      steps {
        sh 'echo "stage2"'
      }
    }

  }
}