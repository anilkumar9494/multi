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
           sh 'echo "testing appl  ication..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
