pipeline {
  agent any
  stages {
    stage('Create File') {
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