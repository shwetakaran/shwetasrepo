pipeline {
  agent any
  stages {
    stage('MergeDev1toQA') {
      steps {
        git(url: 'https://github.com/shwetakaran/shwetasrepo.git', branch: 'dev1', credentialsId: 'sk-git-credentials')
      }
    }

  }
}