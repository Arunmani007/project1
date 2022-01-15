pipeline {
  agent any
  stages {
    stage('test') {
      agent any
      steps {
        sh '''ansible --version
---
host: localhost
task:
  name: install httpd
  shell: apt-get install -y apache2'''
      }
    }

  }
}