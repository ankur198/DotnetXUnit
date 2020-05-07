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
        sh 'dotnet build'
      }
    }

    stage('test') {
      steps {
        sh 'dotnet test'
      }
    }

  }
}