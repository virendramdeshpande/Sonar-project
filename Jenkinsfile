pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                echo %JAVA_HOME%
            }
            steps {
                bat 'dotnet restore' 
            }
            steps {
                bat 'dotnet build --no-restore' 
            }              

        }
    }
}