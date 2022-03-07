pipeline { 
  
   agent any

   stages {
   
     stage('Install anil kumar Dependencies') { 
        steps { 
           sh 'mvn clean' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
