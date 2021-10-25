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
		    echo 'Hello1 World webhook'
       echo 'git ref name is :' + ref
		    echo 'the git base_ref name main is :' + base_ref
               
                      }
        }
   }
}
