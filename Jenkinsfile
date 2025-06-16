pipeline{
  aget any
  environment {
    PATH = "$PATH:/opt/apache-maven-3.6.3/bin"
  }
  stages {
    stage ('GetCode') {
      steps {
        get branch: 'main',
        url: 
          }
    }
    stage ('Build') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}
