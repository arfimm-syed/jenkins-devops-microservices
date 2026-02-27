//SCRIPTED

//DECLARATIVE
pipeline {
agent any
stages {
	stage('Build') {
		steps {
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




