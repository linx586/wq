pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        echo 'wqeqwegfh'
        svn(url: '4567', changelog: true)
      }
    }
    stage('2') {
      steps {
        echo 'safa'
      }
    }
    stage('3') {
      steps {
        echo 'sadasd'
      }
    }
    stage('4') {
      steps {
        sh 'node {         stage (\'Checkout\') {        git \'https://github.com/phodal/growth-studio\'      }         stage (\'Create Virtualenv\') {        sh \'./ci/setup.sh\'      }         stage (\'Install\') {        sh \'./ci/install.sh\'      }         stage (\'Unit Test\') {        sh \'./ci/unit_test.sh\'      }         stage (\'E2E Test\') {        sh \'./ci/e2e.sh\'      }         stage (\'Deploy\') {        sh \'./ci/deploy.sh\'      }    }'
      }
    }
  }
}