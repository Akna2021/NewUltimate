pipeline 
{
    agent any
    environment 
    {
        sciezka = "Program Files"
        dotnet = "C:\\sciezka\\dotnet\\dotnet.exe"
    }
    stages 
    {
        stage('Build') 
        {
            steps 
            {
                bat 'dotnet build'
            }
        }
        stage('Run') 
        {
            steps 
            {
                bat 'dotnet run'
            }
        }
        stage('Clean') 
        {
            steps 
            {
                bat 'dotnet clean'
            }
        }
    }
}