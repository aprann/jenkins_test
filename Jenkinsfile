//this is a comment

pipeline {

	agent any

        environment {
		
		CC= 'clang'
                    }

	stages {
	
		stage('Example') {
		steps{
			sh 'printenv'
  			echo "${currentBuild.result}"
		}
		     }
	}
	post {
		always {
			echo "Test to see if this is run"
			sh "cp -rp * /tmp"
                       }

}
}
