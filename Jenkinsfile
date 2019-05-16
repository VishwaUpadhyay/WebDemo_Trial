pipeline {
    agent any
	
	stages {
		stage ('Stage 1') {
			steps {
				sh 'pwd'
				sh 'python demoapp/server.py'
			}
			
		}
		
		stage ('Stage 21') {
			steps {
				echo 'Second Stage'
			}
		}
	}
}
