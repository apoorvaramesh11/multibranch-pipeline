pipeline {
	agent any

	stages {
	  stage('build') {
	    steps {
		echo 'Building application'
		}
	  }
	  stage('Test') {
   	    steps {
		echo 'Testing the application'
		}
	  }
	  stage('Branch name') {
	    steps {
		echo "current branch: ${env.BRANCH_NAME}"
    		}
	  }
	}
      }
