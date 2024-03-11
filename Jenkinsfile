pipeline {
  agent any
  stages {
	  stage('Build') {
		  steps {
			  script {
                  sh 'chmod +x app.py'
				  sh '/usr/bin/python3 app.py > output.txt'
			  }
		  }
	  }
  }
}