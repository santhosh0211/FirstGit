pipeline {
  agent any
  stages {
    stage('Run Powershell') {
      agent {
        node {
          label 'master'
        }

      }
      steps {
        writeFile(file: 'TestPowershell.txt', text: 'Hello')
      }
    }

  }
}