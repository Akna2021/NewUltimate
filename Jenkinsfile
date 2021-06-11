pipeline {
    agent any
    enviroment
    {
        dotnet = 'C:\Program Files\dotnet\dotnet.exe'
    }
    stages {
        stage('Build') {
            steps {
                bat 'dotnet build'
            }
        }
        stage('Run') {
            steps {
                bat 'dotnet run'
            }
        }
        stage('Clean') {
            steps {
                bat 'dotnet clean'
            }
        }
    }
}