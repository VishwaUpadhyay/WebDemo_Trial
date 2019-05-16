pipeline {
    agent any
	
	stages {
		stage ('Stage 1') {
			steps {
				sh 'pwd'
				sh 'cd demoapp'
				sh 'python server.py'
			}
			
		}
		
		stage ('Stage 21') {
			steps {
				echo 'Second Stage'
			}
		}
	}
}
