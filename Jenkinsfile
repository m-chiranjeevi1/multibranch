node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/m-chiranjeevi1/multibranch.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    stage('Continuous Testing') 
	{
              sh label: '', script: 'echo "Testing Passed"'
	}
}
