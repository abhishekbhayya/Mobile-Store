pipeline{
     agent any
     stages{
         stage('Build the project'){
           steps{
               echo "building the project"
               bat 'mvn clean install -DskipTests'
             }
         }
       stage('Run the maven'){
          steps{
             echo "run the project"
              bat 'mvn spring-boot:run'
       }
      }
    }
  }
        
