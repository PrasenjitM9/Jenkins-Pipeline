pipeline {
    agent { label 'master' }
    #agent any
    stages {
        stage('testing pipeline'){
          steps{
	    echo 'test-first'
            bat 'mkdir from-jenkins'
            bat 'echo > from-jenkins/test.txt'
         }
      }
    }
}
