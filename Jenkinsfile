pipeline
{
	agent any
	tools
	{
	maven "Maven"
	}
	stages{
		stage('Code Checkout'){
			steps{
				git branch: 'main', url: 'https://github.com/CloudGen0007/Maven7AM.git'

			}
		}
		stage('Execute Maven'){
			steps{
				sh 'mvn package'
			}
		}
	}
}
