pipeline {
  agent {
    docker {
      image 'ubuntu'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'echo "In Master branch"'
      }
    }
    stage('Post') {
      steps {
        echo 'Post action'
      }
    }
  }
  post {
    always {
      echo 'Post action fired'
      
    }
    
  }
}