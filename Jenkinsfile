pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                echo %JAVA_HOME% 
                bat 'dotnet restore' 
                bat 'dotnet build --no-restore' 
            }
        }
    }
}