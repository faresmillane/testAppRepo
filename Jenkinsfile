pipeline {

agent {

    label 'slave_2'
  
  
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
