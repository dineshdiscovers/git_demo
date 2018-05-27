pipeline {
  agent any
  stages {
    stage('GIT') {
      steps {
        git 'https://github.com/apache/maven.git'
      }
    }
    stage('error') {
      steps {
        sh '''/usr/local/bin/apache-maven-3.3.9/bin/mvn
package'''
      }
    }
  }
}