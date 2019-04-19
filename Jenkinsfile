pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
              echo "Runing Build Job"
              sh './gradlew build --no-daemon'
              archiveArtifacts artifacts: 'dist/trainschedule.zip'
             }
         }
      }
}
