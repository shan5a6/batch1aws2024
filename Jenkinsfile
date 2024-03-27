pipeline {
	agent any
	stages {
		stage('welcome note') {
			steps {
				script {
					subject="jenskinspac"
					println "value of subject is ${subject}"
					// working with predefined variables
					println "my workspace is ${WORKSPACE}"
					println "my build no is ${BUILD_NUMBER}"
				}				
			}
		}
	}
}
