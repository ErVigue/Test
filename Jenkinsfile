agent {
  docker {
    image "ppiper/jenkins-master"
    args "-u root"
    alwaysPull false
    reuseNode true
  }
}
node {
        stage('Preparation') {
           //Preparations and checkout the code 
            echo "Hello World"
        }
        stage('Build') {
            sh "c:\\ToscaCI\\Client\\ToscaCIClient.exe"
        }  
        stage('Post build action'){
     
            bat '''  ECHO Hello World  '''
    
        }
     }


