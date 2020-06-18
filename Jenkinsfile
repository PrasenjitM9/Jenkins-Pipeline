pipeline {
    agent any
    stages {
        stage('testing pipeline'){
          steps{
	    echo 'test1'
            bat 'mkdir from-jenkins'
            bat 'echo > from-jenkins/test.txt'
         }
      }
    }
}