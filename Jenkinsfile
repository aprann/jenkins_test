//this is a comment

pipeline {

	agent any

	stages {
	
		stage('Build') {
		steps{
			echo "Insert your build command here"
	   		archiveArtifacts artifacts: 'file*' , fingerprint: true
	
		}
		     }
	}
	
}
