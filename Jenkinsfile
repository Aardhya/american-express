pipeline {
  agent none
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/narendrasingamaneni91/american-express.git', branch: 'master', credentialsId: 'narendrasingamaneni91')
      }
    }
  }
}