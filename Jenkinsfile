pipeline {
    agent { docker { image cd_docker/hello } }
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
