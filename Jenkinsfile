pipeline {
  agent any 
  stages {
    stage("Install") {
      steps {
        sh 'echo "Script para instalar o lint"'
               
      }
    }
    stage("Linting"){
	steps {
		sh 'tidy -q -e *.html'
		}
	}
  }
}
