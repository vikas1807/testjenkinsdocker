pipeline {
	//agent any
	agent {docker {image 'maven:3.8.4-openjdk-21'}}
	stages {
		stage('Build') {
			steps {
				sh 'mvn --version'
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
	}
}
