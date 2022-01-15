pipeline {
  agent any
  stages {
    stage('test') {
      agent any
      steps {
        sh 'ansible-playbook test.yml'
      }
    }

  }
}