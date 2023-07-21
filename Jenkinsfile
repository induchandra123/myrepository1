pipeline {
  agent {
    label {
      label 'master'
      customWorkspace '/mnt/myrepository'
    }
  }
  stages {
    stage ('clean workspace') {
			steps {
				cleanWs()
			}
		}
	  
    stage ('23q1 branch index.html') {
      steps {
        echo "23q1 branch"
        sh 'cp -r /mnt/myrepository/index.html /var/www/html'
        sh 'chmod -R 777 /var/www/html/index.html'
      }
    }
  }
}
