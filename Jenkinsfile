pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git url: 'https://github.com/ashwiniitti2005/test.git',
          branch: 'main'
      }
    }
    stage('Run Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
