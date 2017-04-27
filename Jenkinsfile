pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/ProjectSample9/SampleProject.git', poll: true)
      }
    }
  }
}