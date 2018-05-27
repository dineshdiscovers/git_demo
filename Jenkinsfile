pipeline {
  agent any
  stages {
    stage('GIT') {
      steps {
        git 'https://github.com/apache/maven.git'
      }
    }
    stage('package') {
      steps {
        sh '''export JAVA_HOME=/usr/lib/jvm/java-1.8.0
/usr/local/bin/apache-maven-3.3.9/bin/mvn package'''
      }
    }
  }
}