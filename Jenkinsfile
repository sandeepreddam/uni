pipeline
{
   agent any
   tools
  {
    maven 'MAVEN3.9.9'
  }
    stages
  { 
      stage('1)
            {
               sh 'git clone https://github.com/RavitejaAdepudi/javawar.git'
            }
        stage('2')
            {
              sh 'mvn install'
            }
        
  }
}
