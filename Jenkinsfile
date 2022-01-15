pipeline {
  agent any
  stages {
    stage('test') {
      agent any
      steps {
        sh 'ansible-playbook installapache.yml'
      }
    }

  }
}