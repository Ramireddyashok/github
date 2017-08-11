pipeline {
  agent any
  stages {
    stage('') {
      steps {
        build(propagate: true, wait: true, job: 'build', quietPeriod: 1)
      }
    }
  }
  environment {
    samplebuild = '12'
  }
}