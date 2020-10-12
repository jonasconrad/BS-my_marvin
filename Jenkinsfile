pipeline {
  agent any
  stages {
    stage('Disk Space Check') {
      steps {
        sh 'df'
      }
    }
    stage('Daily Dose od Satisfaction') {
      def NAME = 'marvin'
      steps {
        sh 'echo "Hello dear ${NAME}"'
        sh 'date'
        sh 'echo "This is your DDoS number ${env.BUILD_NUMBER}"'
      }
    }
  }
}