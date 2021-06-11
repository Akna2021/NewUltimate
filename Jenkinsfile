pipeline 
{
    agent any
    environment 
    {
        dot = 'C:\\"Program Files"\\dotnet\\dotnet.exe'
    }
    stages 
    {
        stage('Build') 
        {
            steps 
            {
                bat "${env.dot} build --configuration Release"
            }
        }
        stage('Run') 
        {
            steps 
            {
                bat "${env.dot} run"
            }
        }
        stage('Clean') 
        {
            steps 
            {
                bat "${env.dot} clean"
            }
        }
    }
}