
pipeline{
    agent any
    stages
    {
         stage('login to database'){
          steps{
             
              echo "."
              sh 'psql -u postgres psql -p postgres '
          }
      }
      stage('Import data from files'){
          steps{
             
              echo "."
              sh 'create database demo4;'
          }
      }
    }
}
