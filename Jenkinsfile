pipeline {
  agent {
    label {
      label 'master'
      customWorkspace '/mnt/myrepository'
    }
  }
  stages {
    stage ('23q2 branch index.html') {
      steps {
        echo "23q2 branch"
        sh 'cp -r /mnt/myrepository/index.html /var/www/html'
        sh 'chmod -R 777 /var/www/html/index.html'
      }
    }
  }
}
