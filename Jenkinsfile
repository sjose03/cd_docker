pipeline {
    agent { docker { image cd_docker/hello } }
      stages {
        stage('log version info') {
      steps {
        echo 'Rodei'
      }
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
