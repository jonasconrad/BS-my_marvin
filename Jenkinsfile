pipeline {
  agent any
    parameters{
      string(name: 'NAME', defaultValue: 'marvin')
    }
  stages {
    stage('Disk Space Check') {
      steps {
        sh 'df'
      }
    }
    stage('Daily Dose od Satisfaction') {
      steps {
        echo "Hello dear ${params.NAME}"
        sh 'date'
        echo "This is your DDoS number ${env.BUILD_NUMBER}"
      }
    }
  }
}