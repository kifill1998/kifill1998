pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        sh 'echo \'Building..\''
      }
    }

    stage('Test') {
      steps {
        sh "mvn clean verify"
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }

  }
}
