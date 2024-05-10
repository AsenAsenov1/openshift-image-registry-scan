pipeline {
  agent any
	
  stages {
	stage('Initial') {
	  steps {
		script {
		  sh 'for x in {1..255}; do echo $x; done'
		}
	  }
	}
  }
}
