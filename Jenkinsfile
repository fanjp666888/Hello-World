pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo 'Hello World Jenkins!!'
				
			}
		}
	}
}
post {
	changed {
		echo "pipeline post changed"
	}
	always {
		echo "pipeline post always"
	}
	success {
		echo "pipeline post success"
	}
	failure {
		echo "pipeline post failure"
	}
}

