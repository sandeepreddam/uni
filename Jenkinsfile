pipeline
{
   agent any
   tools
  {
    maven 'MAVEN3.9.9'
  }
    stages
  { 
      stage('1')
            {
               steps
               {
               sh 'git clone https://github.com/RavitejaAdepudi/javawar.git'
               }
            }
         stage('2')
        {
              steps
        {
           sh 'mvn -f /var/lib/jenkins/workspace/three/javawar/pom.xml
        }
       }
   
     }
        
  }
   

