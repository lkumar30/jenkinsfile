#!/usr/bin/env groovy

node{

	stage('SCM-code_grab'){
		steps{
			sh 'echo "hello-world"'
			sh 'echo "scm grab"'
		}	

			}


	stage('jira_integration'){
		steps{
			echo 'integrating jira'
			echo 'second hellow-world'
		}
			}	

	stage('Maven_build'){
		steps{
			echo 'maven build'
			echo 'third hello-world'
			}
		}


	stage('Deploy_to_nexus'){
		steps{	
			echo 'fourth hello-world'
			echo 'deploy to nexus'
		}
			}

	stage('deploy_to_tomcat'){
		steps{
			echo 'last hellow-world'
			echo 'deployed to tomcat'
		}
			}

	

}
