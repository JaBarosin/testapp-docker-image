pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo 'testapp-docker step 1'
      }
    }

    stage('img scan status') {
      steps {
        slackSend(botUser: true, baseUrl: 'https://app.slack.com/client/T021A01BXLH', token: 'xapp-1-A021P31GTC0-2034999533555-4129abb45fb9f0e3b9805a95e5d6b1952f0f48e338129cdf7ca4c1f795d0140a', channel: '#image-scans', message: 'test-pipeline testing')
      }
    }

  }
  environment {
    test = 'test'
  }
}