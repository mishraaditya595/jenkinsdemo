pipeline { 
    agent any  
    stages { 
        stage('sample1') {
          steps {
            echo 'summition'
          }
        }
        stage('sample 2') { 
            steps { 
               echo 'addition...' 
               sh 'python3 hello.py'
              //bat 'mvn package'
            }
        }
   
}
    }
