pipeline {
  agent any
  stages {
    stage('deploy to server') {
      steps {
        sh '''ssh -f ssh root@143.110.230.201
git clone https://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@github.com/ifycodeNg/vue-repo.git
cd vue-repo'''
      }
    }

  }
}