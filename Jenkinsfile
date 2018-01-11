pipeline {
    /*agent {
    	docker { image 'ubuntu' }
    }*/
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "In Master branch"'
            }
        }
    }
    post {
        always {
            echo 'Post action fired'
        }
    }
}
