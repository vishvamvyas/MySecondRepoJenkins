pipeline {
	 agent any 
	 
	 stages {
		stage("compile") {
			steps {
				echo "Compiling"
				bat """ javac MyJava.java """
				}
			}
			
		stage ("run") {
			steps {
				echo "Running"
				bat """ java MyJava"""
				}
			}
			
		}
	}