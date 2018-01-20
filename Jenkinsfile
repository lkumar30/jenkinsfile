#!/usr/bin/env groovy


	node{

		stage('SCM-code_grab'){
					checkout scm
					sh 'echo "hello-world"'
					sh 'echo "scm grab"'
			

					}

	
		stage('jira_integration'){
					echo 'integrating jira'
					echo 'second hellow-world'
					}	

		stage('Maven_build'){		
					echo 'maven build'
					echo 'third hello-world'
					}


		stage('Deploy_to_nexus'){
					echo 'fourth hello-world'
					echo 'deploy to nexus'
					}

		stage('deploy_to_tomcat'){
					echo 'last hellow-world'
					echo 'deployed to tomcat'
					}
	}
		
		
     