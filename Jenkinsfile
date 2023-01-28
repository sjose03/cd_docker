pipeline {
   stages {
    stage('Start Build')
    {
        agent 
           {
             docker { image 'node:10.16.3-alpine' }
           }
        steps 
           {
       echo "Rodei:"
           } 
    }
   } 
   post {
    success 
        {
            echo "Deu bom"
        }
    failure 
        {
            echo "Deu ruim"
        }
    aborted 
        {
            echo "Deu ruim"
        }
    }   
}
