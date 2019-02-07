pipeline {
 adent any
  stages {
     stage ('build') {
     steps  {
     echo 'Running build aautomation'
     sh './gradlew build --no-deamon'
     archiveArtifacts artifact: 'dist/trainSchedule.zip
     }
     }
     }
     } 
  
