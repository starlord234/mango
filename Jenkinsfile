pipeline{
   agent any
       stages{
          stage('get code from github'){
            steps{
                echo 'get latest code'
              git 'https://github.com/starlord234/mango.git'
           }
	
       }

          stage('compiling java code'){
             steps{
              sh 'javac heloworld.java'
           }
        }
          stage('running java code'){
            steps{
              sh 'java heloworld'
          }
       }
    }
}
