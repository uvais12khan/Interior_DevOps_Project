pipeline {
  agent any
  stages {
    stage('') {
      steps {
        retry(count: 1) {
          git(url: 'https://github.com/Areez01/devops-project.git', branch: 'dev')
        }

      }
    }

  }
}