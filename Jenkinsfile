pipeline { 
  
   agent any

   stages {
   
     stage('Install anil kumar Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing appl  ication..."'
        }
      }

         stage("Deploy appl  ication") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
