pipeline {
    /*agent {
    	docker { image 'ubuntu' }
    }*/
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "In Production branch"'
            }
        }
    }
    post {
        always {
            echo 'Post action fired'
        }
    }
}
