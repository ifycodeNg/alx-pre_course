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