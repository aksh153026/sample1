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
		    bat "${ref}"
		    echo 'git ref name is :' + ref
		    echo 'the git base_ref name dev is :' + base_ref
               
                      }
        }
   }
}
