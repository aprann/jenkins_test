//this is a comment

pipeline {

	agent any

	stages {
	
		stage('Build') {
		steps{
			sh echo "Insert your build command here"
	   		archiveArtifacts artifacts: '*.txt' , fingerprint: true
	
		}
		     }
	}
	
}
