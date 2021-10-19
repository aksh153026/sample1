pipeline {    
  agent {
      label 'master'
  } 
 
   stages {
	stage('Checkout SCM') {
            steps {
		    echo 'Hello World webhook'
       echo 'git repository name is : $ref'
		    echo 'git repository name is :' + base_ref
               
                
            }
        }
   }
}
