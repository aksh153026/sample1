pipeline {    
  agent {
      label 'master'
  } 
 options {
    skipDefaultCheckout true
  }
   stages {
	stage('Checkout SCM') {
            steps {
		    echo 'Hello World webhook'
       echo 'git repository name is :' + ref
		    echo 'git repository name is :' + base_ref
               
                
            }
        }
   }
}
