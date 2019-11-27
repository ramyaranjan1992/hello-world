pipeline {
  agent none
  stages {
    stage('compile Java') {
      steps {
        sh 'javac HelloWorld.java'
      }
    }

    stage('Run Java') {
      steps {
        sh 'java HelloWorld'
      }
    }

  }
}