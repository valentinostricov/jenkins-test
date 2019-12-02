pipeline{
    options {
     ansiColor('gnome-terminal')
     timestamps()
     disableConcurrentBuilds()
    }
    agent {
    label 'MobileDaily01'
    }

    stages {
        stage('Checkout') {
            steps {
                script {
                    echo "THIS IS A PR"
                    checkout scm
                }
            }
        }
    }
  }
