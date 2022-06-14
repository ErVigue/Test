
node {
        stage('Preparation') {
           //Preparations and checkout the code 
            "C:\\ToscaCI\ToscaCIRemoteExecutionService.exe"
        }
        stage('Build') {
            "C:\\ToscaCI\\Client\\ToscaCIClient.exe" -m local -r C:\\Temp\\ToscaCI.xml
        }  
        stage('Post build action'){
     
            bat '''  Closing the server  '''
    
        }
     }


