node{
	stage('Execute Ansible')
	{
	   ansiblePlaybook credentialsId: 'private', disableHostKeyChecking: true, installation: 'ansible2', inventory: 'dev.ini', playbook: 'tomcat.yml'
	}
}
