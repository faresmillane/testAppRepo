pipeline {

agent {

    label 'slave_2'
  
  
}


stages {
         stage("Prepare"){
       steps{
         sh '''
           sh ./test_jenkins.sh
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
