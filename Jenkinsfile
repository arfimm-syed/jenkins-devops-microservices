//SCRIPTED

//DECLARATIVE
pipeline {
agent {docker { image 'node:25.7.0' } }
stages {
	stage('Build') {
		steps {
			sh 'node --version'
	    	echo "BUild"
		}
	}   
	stage('Test') {
		steps {	   
	       echo "Test"
		}
	}
	stage('Integration') {
		steps {       
		   echo "Integration Test"
		}
	}
		} 
		
	post {
			always {
			    echo "I am Awesome, I run always"
			}
			success {
			    echo "I run when yu are successful"	
			}
			failure {
				echo "I run when you fail"
			}
		}
	}




