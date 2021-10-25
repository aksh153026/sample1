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
		    echo 'git ref name is $.{ref}:' + ref
		    echo 'the git base_ref name dev is :' + base_ref
               
                      }
        }
   }
}
