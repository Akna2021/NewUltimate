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
                bat '$dot build'
            }
        }
        stage('Run') 
        {
            steps 
            {
                bat 'dot run'
            }
        }
        stage('Clean') 
        {
            steps 
            {
                bat 'dot clean'
            }
        }
    }
}