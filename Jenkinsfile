pipeline {
    /*agent {
    	docker { image 'ubuntu' }
    }*/
    agent any
    /*triggers {
        cron('0 * * * *')
    }*/
    stages {
        stage('Build') {
            steps {
                sh 'echo "In Production branch with trigger"'
            }
        }
    }
    post {
        always {
            echo 'Post action fired'
        }
    }
}
