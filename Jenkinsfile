pipeline{ 
  agent none
stages{
     stage("Bulid Java 7"){
	 
	 agent {
   	 docker "openjdk:7"
	 }
      steps {
	    
      } 
    }
	stage ("Build java 8")
	{
	agent { docker "openjdk:8"}
	steps{
	 
	}
	}
  }
}