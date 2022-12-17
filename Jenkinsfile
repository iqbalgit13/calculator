pipeline {	 
	agent any
        tools {
    	maven 'MAVEN_HOME'
	}	 
    	stages {     	 
    	stage("Compile") {          	 
            	steps {               	 
                	sh "mvn compile"          	 
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {               	 
                	sh "mvn test"          	 
            	}     	 
        	}	 
    	}
}

