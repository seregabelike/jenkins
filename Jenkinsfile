pipeline {
  agent any

  stages {
    stage ('hey') {
      steps {
        echo "hey, little one"
      }
    }
    stage ('two') {
      steps {
        sh 'ls -la /etc'
        sh  'date'
       }
    }
  }



}
