pipeline {
  agent any
  stages {
    stage('deploy to server') {
      environment {
        pass = '02CdAw5zg@!dp3KYZ'
      }
      steps {
        sh '''#!/bin/bash
ssh root@146.190.48.106 
git clone \'https://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@github.com/ifycodeNg/vue-repo.git\'
cd vue-repo'''
      }
    }

  }
}