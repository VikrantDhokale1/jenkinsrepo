pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pwd
cal'''
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'echo "hello india"'
          }
        }

        stage('test par') {
          steps {
            sleep(time: 10, unit: 'SECONDS')
          }
        }

      }
    }

  }
}