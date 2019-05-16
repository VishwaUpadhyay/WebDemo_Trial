pipeline {
    agent any
	
	stages {
		stage ('Stage 1') {
			echo 'First Stage'
		}
		
		stage ('Stage 21') {
			echo 'Second Stage'
		}
	}
}