pipeline {
   agent {
        docker { image 'mcr.microsoft.com/dotnet/core/aspnet:3.1' }
	}
    stages {
        stage('Build') {
            steps {
                sh 'dotnet restore'
                sh 'dotnet build'
            }
        }
    }
}