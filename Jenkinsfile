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
      }
    }
  }
}
