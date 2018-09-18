pipeline {
  agent any
  stages {
    stage('first') {
      steps {
        echo 'this is the message'
      }
    }
    stage('second') {
      steps {
        git(url: 'https://github.com/Vishwas1976/game-of-life.git', branch: 'master', poll: true)
      }
    }
  }
}