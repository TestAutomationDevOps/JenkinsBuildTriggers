pipeline
{
	agent any
	
	stages
	{
		stage('Git Clone')
		{
			steps()
			{
				git branch: 'master', url: 'https://github.com/TestAutomationDevOps/JenkinsBuildTriggers.git'
				echo "Source Code is Successfully Pulled from GitHub to Jenkins Workspace..!!"
			}
		}
	}
}
