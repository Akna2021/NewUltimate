pipeline 
{
    agent any
    environment 
    {
        sciezka = "Program Files"
        dot1 = 'C:\\' 
        dot2 = '\\dotnet\\dotnet.exe'
        dot = dotnet.Join(dot1, sciezka, dot2)
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