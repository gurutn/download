pipeline {
  agent {
    node {
      label 'Test_node'
    }

  }
  stages {
    stage('trigger') {
      steps {
        pysh(script: 'der.py', returnStatus: true, returnStdout: true)
      }
    }

  }
}