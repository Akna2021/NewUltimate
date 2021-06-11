pipeline 
{
    agent any
    environment 
    {
        sciezka = "Program Files"
        dot = ("C:\\", sciezka, "\\dotnet\\dotnet.exe")
    }
    stages 
    {
        stage('Build') 
        {
            steps 
            {
                bat 'dot build'
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