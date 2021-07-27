pipeline {
	agent {
	label 'agent1'
	}
    stages {
        stage('Deploy') {
            steps {
         	sh 'sudo docker-compose up -d'
                  }
		}
	}
}
