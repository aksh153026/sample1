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
       echo 'git ref name is :' + ref
		    echo 'git base_ref name is :' + base_ref
               
                      }
        }
   }
}
