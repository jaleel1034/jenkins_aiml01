pipeline{
  agent any
       stages{
           stage('validation'){
              steps{
                echo 'i am validating the code'
                   }
                              }
           stage('compiling'){
              steps{
                echo 'i am compiling the code'
                   }
                              }
           stage('instal'){
              steps{
                echo 'i am installing the code'
                   }
                              }
           stage('deploy'){
              steps{
                echo 'i am depolying the code'
                   }
                              }
