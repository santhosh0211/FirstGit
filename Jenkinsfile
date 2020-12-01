pipeline {
  agent any
  stages {
    stage('Run Powershell') {
      agent {
        node {
          label 'Node_1'
        }

      }
      steps {
        writeFile(file: 'Test.txt', text: 'Hello')
      }
    }

  }
}