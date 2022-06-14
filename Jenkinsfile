
node {
        stage('Preparation') {
           //Preparations and checkout the code 
            echo "preparing"
        }
        stage('build') {
            steps {
                script {
                  "C:\ToscaCI\Client\ToscaCIClient.exe" -m local -r C:\Temp\ToscaCI.xml             
                }
        stage('Build') {
            bat "C:\ToscaCI\Client\ToscaCIClient.exe" -m local -r C:\Temp\ToscaCI.xml
        }  
        stage('Post build action'){
     
            bat '''  Closing the server  '''
    
        }
     }


