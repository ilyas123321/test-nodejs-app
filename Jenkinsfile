pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies with more option') { 
        steps { 
           sh 'echo "installing dependencies..."'
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
