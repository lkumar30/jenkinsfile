#!/usr/bin/env groovy
pipeline{


	//node{
	
	agent none
	stages{
		
		stage('SCM-code_grab'){


// to grab the source code that has maven repo too in to the workspace
			steps{
					checkout scm
					sh 'echo "hello-world"'
					sh 'echo "scm grab"'
			}

					}

	
		stage('jira_integration'){
					echo 'integrating jira'
					echo 'second hellow-world'
					}	

		stage('Maven_build'){
	
// maven build from  the repo	
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
		
		
	}     
//}