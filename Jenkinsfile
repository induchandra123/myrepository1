pipeline {
  agent {
    label {
      label: master
    }
  }
  stages {
    stage ('main branch index.html') {
      steps {
        sh 'cp -r index.html /var/www/html'
        sh 'chmod -R 777 /var/www/html'
      }
    }
  }
}
