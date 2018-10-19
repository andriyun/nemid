pipeline {
  agent {
    docker {
      image 'drupal:8-fpm-alpine'
    }

  }
  stages {
    stage('') {
      agent {
        docker {
          image 'drupal:8-fpm-alpine'
        }

      }
      steps {
        echo 'Hello world'
      }
    }
  }
}