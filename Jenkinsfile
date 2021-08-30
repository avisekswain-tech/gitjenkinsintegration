pipeline {
agent any
	stages {
		stage ('git pull'){
			steps {
			git branch: 'main', credentialsId: 'github-cerd', url: 'https://github.com/avisekswain-tech/gitjenkinsintegration.git'
			}
			
		}
		stage ('testing'){
			steps {
			sh "echo 'testing'"
			}
			
		}
		stage ('testing2'){
			steps {
			sh "echo 'testing2'"
			}
			
		}
	}
}
