pipeline {
    agent {
      kubernetes {
        label 'jenkins-slave'
        defaultContainer 'jnlp'
      }
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
              sh 'env'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
