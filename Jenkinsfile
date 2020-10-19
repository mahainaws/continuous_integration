pipeline {
	agent any
	stages {
		stage("Clone") {
			steps {
				echo 'Code is being pulled from GitHub'
				sleep 6
				echo 'Cloning is Completed'
			}
		}
		
		stage("Compile") {
			steps {
				echo 'Code compilation is in Progress'
				sleep 5
				echo 'Compilation is Completed'
			}
		}
		
		stage("Unit Testing") {
			steps {
				echo 'Unit Testing is in Progress'
				sleep 8
				echo 'Unit Testing is Completed'
			}
		}
		
		stage("Integration Testing") {
			steps {
				echo 'Integration Testing is in Progress'
				sleep 11
				echo 'Integration Testing is Completed'
			}
		}
		
		stage("Packaging") {
			steps {
				echo 'Packaging in Progress'
				sleep 4
				echo 'Packaging is completed'
			}
		}
		
		stage("Push Artifacts") {
			steps {
				echo 'Pushing Artifacts to Nexus'
				sleep 5
				echo 'Artifcats are pushed to Nexus'
			}
		}
}
}
