pipeline {    
  agent {
      label 'master'
  } 
	options {
    skipDefaultCheckout true
  }
    tools {
        git 'Default'
        nodejs 'NodeJS'
        maven 'MAVEN_HOME' 
        jdk 'jdk1.8' 
    }
 
   stages {
	stage('Checkout SCM') {
            steps {
		    echo 'Hello World webhook'
       echo 'git repository name is : $ref"
		    echo 'git repository name is :' + base_ref
               
                
            }
        }
   }
}
