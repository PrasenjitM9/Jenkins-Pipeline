pipeline {
    agent { label 'master' }
    /* agent any */
    stages {
        stage('testing pipeline'){
          steps{
	    echo 'test-first'
	    sh 'mkdir from-jenkins'
            sh 'echo > from-jenkins/test.txt'
            /* bat 'mkdir from-jenkins'
            bat 'echo > from-jenkins/test.txt'
	    */
         }
      }
    }
}
