pipeline {
  agent any 
  stages {
    stage("Install") {
      steps {
        sh 'echo "Script para instalar o lint"'
        sh 'sudo apt install tidy'
               
      }
    }
    stage("Linting"){
	steps {
		sh 'tidy -q -e *.html'
		}
	}
  }
}
