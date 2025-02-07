pipeline {
	agent any {
	stages {
		stage (create_file) {
			steps {
				touch file
			}
		}
		stage (echo) {
			steps {
				echo "Hello from Pipeline!
			}
		}
	}
	}
}
