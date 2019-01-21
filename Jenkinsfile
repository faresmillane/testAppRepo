pipeline {

agent {

    label 'slave'
  
  
}


stages {
         stage("Prepare"){
       steps{
         sh '''
           pwd    
           ls     
           npm install
           '''
         }
     }

     stage ("Build"){
       steps {
         sh '''
           echo "Building app"
         '''
       }
     }
}


}
