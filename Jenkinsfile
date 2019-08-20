pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo 'Hello World Jenkins!!'
				echo $(cd $(dirname $0); pwd)
			}
		}
	}
}

