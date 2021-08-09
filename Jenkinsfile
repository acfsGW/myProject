pipeline 
{
  agent any
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
        //sh 'mvn clean compile'
        sh 'echo "Dummy build"'
      }
    }
    
  }
}
