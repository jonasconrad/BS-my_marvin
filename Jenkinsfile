pipeline {
  agent any
  parameters {
      string(name: 'NAME', defaultValue: 'marvin')
      wrap([$class: 'BuildUser']) {
        var name = "${BUILD_USER}"
      }
  }
  stages {
    stage('Disk Space Check') {
      steps {
        sh 'df'
      }
    }
    stage('Daily Dose od Satisfaction') {
      steps {
        echo "The current user is: ${params.name}"
        echo "Hello dear ${params.NAME}"
        sh 'date'
        echo "This is your DDoS number ${env.BUILD_NUMBER}"
      }
    }
  }
}