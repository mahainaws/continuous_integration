pipeline {
	agent any
	stages {
		stage("Clone") {
			steps {
				echo 'Clone is in Progress'
				sleep 4
				echo 'Clone is Completed'
			}
		}
		
		stage("Compile") {
			steps {
				echo 'Code compilation is in Progress'
				sleep 3
				echo 'Compilation is Completed'
			}
		}
		
		stage("Unit_Testing") {
			steps {
				echo 'Unit Testing is in Progress'
				sleep 7
				echo 'Unit Testing is Completed'
			}
		}
		
		stage("Integration_Testing") {
			steps {
				echo 'Integration Testing is in Progress'
				sleep 4
				echo 'Integration Testing is Completed'
			}
		}

		stage("Test_Coverage") {
			steps {
				echo 'Test Coverage in Progress'
				sleep 5
				echo 'Test Coverage is Completed'
			}
		}
		
		stage("Packaging") {
			steps {
				echo 'Packaging in Progress'
				sleep 3
				echo 'Packaging is completed'
			}
		}
}
}