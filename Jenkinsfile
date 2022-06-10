pipeline{
   agent any
 stages {
  stage('compilation') {
    steps {
      sh 'mvn compile'
    }
  }
}
 stage('package') {
  steps {
    sh 'mvn package'
  }
}
 }
