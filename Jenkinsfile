pipeline {
    agent any
    options {
        timetamps()
    }
    stages {
       stage ('mvn checkout') {
           steps {
              echo "checkoutupdater"
      }
   }
}
       stage ('init') {
           steps {
               script {
                   LOCATION_PATH = "$(env.WORKSPACE)"
                   echo "$LOCATION_PATH"  
       }
     }
   }
}
