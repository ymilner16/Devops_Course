pipeline {
	agent any 
	stages {
		stage('create_file') {
			steps {
				sh "touch file"
			}
		}
		stage('echo') {
			steps {
				echo "Hello from Pipeline!"
			}
		}
	}
	
}
