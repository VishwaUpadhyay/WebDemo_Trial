pipeline {
    agent any
	
	stages {
		
		stage ('Stage 1 - Deploy the server') {
			steps {
				echo 'Starting the Demo Server'
				bat 'START "" python server.py'
			}
			
		}
		stage ('Stage 2 - Execute the tests') {
			steps {
				 bat 'robot login_tests'
			}
			
		}
	}
}
