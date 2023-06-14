pipeline {
  agent {
    node {
      label 'voting'
    }

  }
  stages {
    stage('Clone') {
      steps {
        echo '1.Clone Stage'
      }
    }

    stage('Test') {
      steps {
        echo '2.Test Stage'
      }
    }

    stage('Build') {
      steps {
        echo '3.Build Stage'
      }
    }

    stage('Deploy') {
      steps {
        echo '4. Deploy Stage'
      }
    }

  }
}