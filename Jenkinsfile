pipeline {
    /*agent {
    	docker { image 'ubuntu' }
    }*/
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
            }
        }
    }
    post {
        always {
            echo 'Post action fired'
        }
    }
}
