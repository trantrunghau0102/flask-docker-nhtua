	// git repository info
	def gitRepository = 'https://github.com/trantrunghau0102/Obo-SpringBoot-MySQL'
	def gitBranch = 'master'

	// gitlab credentials
	def gitlabCredential = 'jenkin_gitlab'	

	pipeline {
		agent any
				
		stages {		
			stage('Checkout project') 
			{
			  steps 
			  {
				echo "checkout project"
				git branch: gitBranch,
				   url: gitRepository
				sh "git reset --hard"				
			  }
			}
		}
	}
