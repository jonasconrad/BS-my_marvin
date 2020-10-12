pipeline {
  agent any
  stages {
    stage('Disk Space Check') {
      steps {
        df
      }
    }
    stage('Daily Dose od Satisfaction') {
      steps {
        echo "Hello dear marvin"
        date
        echo "This is your DDoS number ${env.BUILD_NUMBER}"
      }
    }
  }
}