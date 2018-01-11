pipeline {
    /*agent {
    	docker { image 'ubuntu' }
    }*/
    agent any
    triggers {
        cron('* * * * *')
    }
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
