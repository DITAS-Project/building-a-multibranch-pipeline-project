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
