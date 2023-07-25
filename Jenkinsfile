node('built-in') 
{
    stage('Continuous Download_master') 
	{
    git branch: 'main', url: 'https://github.com/saikurmapu/demo'
	}
    stage('Continuous Build_master') 
	{
    sh label: '', script: 'mvn package'
	}
}
