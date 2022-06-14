
node {
        stage('Preparation') {
           //Preparations and checkout the code 
            bat "C:\ToscaCI\ToscaCIRemoteExecutionService.exe"
        }
        stage('Build') {
            bat "C:\ToscaCI\Client\ToscaCIClient.exe" -m local -r C:\Temp\ToscaCI.xml
        }  
        stage('Post build action'){
     
            bat '''  Closing the server  '''
    
        }
     }


