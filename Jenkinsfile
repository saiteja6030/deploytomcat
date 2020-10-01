node{
	stage(' Checkout')
		{
		  git branch: 'master', url: 'https://github.com/saiteja6030/tomans.git'
		}
	
	stage('Execute Ansible')
	{
		ansiblePlaybook credentialsId: 'private', disableHostKeyChecking: true, installation: 'ansible2', inventory: 'dev.ini', playbook: 'testing.yml'
		
	}
		
}
