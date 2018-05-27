pipeline {
  agent any
  stages {
    stage('GIT') {
      steps {
        git 'https://github.com/apache/maven.git'
      }
    }
    stage('') {
      steps {
        sh '/root/apache-maven-3.3.9/bin/mvn --version'
      }
    }
  }
}