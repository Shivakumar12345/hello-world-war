pipeline {
  agent any
  stages {
    stage('fetch') {
      steps {
        git(url: 'https://github.com/Shivakumar12345/hello-world-war.git', branch: 'master')
      }
    }

    stage('Build') {
      steps {
        sh 'sh \'mvn clean package\''
      }
    }

  }
}