pipeline {
  agent any
  stages {
    stage('restore dependencies') {
      steps {
        sh 'dotnet restore'
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