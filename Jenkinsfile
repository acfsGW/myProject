pipeline 
{
  agent any
  tools
  {
    maven 'maven-3.8.1'
  }
  stages 
  {
    stage('checkout') 
    {
      steps 
      {
        git 'https://github.com/effectivejenkins/myProject.git'
      }
    }
    stage('Build') 
    {
      steps 
      {
        sh 'mvn clean compile'        
      }
    }
    
  }
}
