pipeline {
    agent any
	
	stages {
		stage ('Stage 1') {
			steps {
				cd demoapp
				python server.py
			}
			
		}
		
		stage ('Stage 21') {
			steps {
				echo 'Second Stage'
			}
		}
	}
}
