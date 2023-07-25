node('built-in') 
{
    stage('Continuous Download_Loans') 
	{
    git branch: 'main', url: 'https://github.com/saikurmapu/demo'
	}
    stage('Continuous Build_Loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
