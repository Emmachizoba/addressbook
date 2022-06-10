pipeline{
   agent any
 stages {
  stage('compilation') {
    steps {
      sh 'mvn compile'
    }
  }

}
 stages {
  stage('package') {
    steps {
      sh 'mvn package'
    }
  }

}

}
