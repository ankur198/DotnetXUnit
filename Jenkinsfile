pipeline {
  agent any
  stages {
    stage('restore dependencies') {
      steps {
        bat 'dotnet restore'
      }
    }

    stage('build') {
      steps {
        bat 'dotnet build'
      }
    }

    stage('test') {
      steps {
        bat 'dotnet test'
      }
    }

  }
}