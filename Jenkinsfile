pipeline {
    agent any
	
	stages {
		
		stage ('Stage 1') {
			steps {
				echo 'Cloning is complete'
			}
			
		}
		stage ('Stage 2') {
			steps {
				timeout(time: 20, unit: 'SECONDS'){
					bat 'python demoapp/server.py'
				}
			}
			
		}
		
		stage ('Stage 21') {
			steps {
				echo 'Second Stage'
			}
		}
	}
}
