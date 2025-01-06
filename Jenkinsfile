pipeline{
  agent: none
  stages{
     stage("Build){
       agent {
         node {
            label "aws-slave"
            customWorkspace "/home/ec2-user/customWorkspace"
              }
          }
         options {
             echo "hello world"
         }      
       }
     }
  }
