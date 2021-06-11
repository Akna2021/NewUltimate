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
                bat "${env.dotnet} build --configuration Release"
            }
        }
        stage('Run') 
        {
            steps 
            {
                bat "${env.dotnet} run"
            }
        }
        stage('Clean') 
        {
            steps 
            {
                bat "${env.dotnet} clean"
            }
        }
    }
}