pipeline {
  agent {
    label {
      label 'master'
      customWorkspace '/mnt/myrepository'
    }
  }
  stages {
    stage ('main branch index.html') {
      steps {
        echo "main branch"
        sh 'cp -r /mnt/myrepository/index.html /var/www/html'
        sh 'chmod -R 777 /var/www/html/index.html'
      }
    }
  }
}
