pipeline {
  agent {
    docker {
      image 'python'
    }

  }
  stages {
    stage('Build') {
      agent {
        docker {
          image 'python'
        }

      }
      environment {
        ok = 'ok'
      }
      steps {
        build 'Build'
      }
    }

    stage('') {
      steps {
        sh 'sh build.sh'
      }
    }

  }
}