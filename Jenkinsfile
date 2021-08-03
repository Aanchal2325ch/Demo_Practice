pipeline {
  agent any
  stages {
    stage('Git Check Out') {
      steps {
        git(url: 'https://github.com/Aanchal2325ch/Demo_Practice.git', branch: 'main')
        echo 'SuccessFul checkout from github'
      }
    }

    stage('Compile') {
      steps {
        bat '.project'
        echo 'Compile successfully'
      }
    }

    stage('Deploy') {
      steps {
        bat '.project'
        echo 'Deploy Successful'
      }
    }

  }
}