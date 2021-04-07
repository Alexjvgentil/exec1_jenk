pipeline {
  agent any 
  stages {
    stage("Install") {
      steps {
        sh 'echo "Script para instalar o lint"'
        sh 'sudo apt install tidy'
               
      }
    }
    stage('Lintint'){
	stesp {
		sh 'tidy -q -e *.html'
		}
	}
  }
}
