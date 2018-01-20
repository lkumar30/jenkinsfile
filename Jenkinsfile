#!/usr/bin/env groovy
pipeline{
	
	agent none


	 tools { 
        maven 'maven-3.5.2' 
        //jdk 'jdk8' 
    }
	
	stages{
		stage('first'){
			steps{
				echo 'hello-world1'
				}
				}
				
		stage('second'){
			steps{
				echo 'hellowworld-2'
				
    //${workspace} will now contain an absolute path to job workspace on slave
				sh 'cd /var/jenkins_home/workspace/simple_java'
				sh 'mvn   install'
				}
	}
	}				

}	