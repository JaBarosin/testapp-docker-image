pipeline {
  agent any
  stages {
    stage('') {
      steps {
        echo 'testapp-docker step 1'
        sh '''Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image \'jbarosin/testapp:latest\' } }
    stages {
        stage(\'build\') {
            steps {
                sh \'python3 --version\'
            }
        }
    }
}'''
      }
    }

  }
  environment {
    test = 'test'
  }
}