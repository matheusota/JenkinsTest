// Declarative //
pipeline {
	agent any
	
	stages {
		stage('Build') {
			steps {
				sh 'echo "Pulling/Compiling source code" '
			}
	}
	
		stage('Test'){
			steps {
				sh 'echo "Testing..." '
			}
		}
		
		stage('Package') {
			steps {
				sh 'echo "Packaging..." '
			}
		}
	}
}
