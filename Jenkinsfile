pipeline {
	agent any
	
	stages {
	    stage('Checkout') {
	        steps {
			checkout scm			       
		      }}
		stage('Build') {
	           steps {
			  sh '/home/swapnil/Documents/DevOps-softwares/apache-maven-3.9.0/bin/mvn install'
	                 }}
		stage('Deployment'){
		    steps {
			
			sh 'cp target/flipkart.war /home/swapnil/Documents/DevOps-softwares/apache-tomcat-9.0.72/webapps'
	}
}}}
