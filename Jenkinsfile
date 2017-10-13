pipeline {
  agent any
  stages {
    stage('ghjk') {
      steps {
        echo 'wqeqwegfh'
        svn(url: '4567', changelog: true)
        sh 'node {         stage (\'Checkout\') {        git \'https://github.com/phodal/growth-studio\'      }         stage (\'Create Virtualenv\') {        sh \'./ci/setup.sh\'      }         stage (\'Install\') {        sh \'./ci/install.sh\'      }         stage (\'Unit Test\') {        sh \'./ci/unit_test.sh\'      }         stage (\'E2E Test\') {        sh \'./ci/e2e.sh\'      }         stage (\'Deploy\') {        sh \'./ci/deploy.sh\'      }    }'
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
        sh 'node {        Â stage (\'Checkout\') {     Â  Â git \'https://github.com/phodal/growth-studio\'     Â }        Â stage (\'Create Virtualenv\') {     Â  Â sh \'./ci/setup.sh\'     Â }        Â stage (\'Install\') {     Â  Â sh \'./ci/install.sh\'     Â }        Â stage (\'Unit Test\') {     Â  Â sh \'./ci/unit_test.sh\'     Â }        Â stage (\'E2E Test\') {     Â  Â sh \'./ci/e2e.sh\'     Â }        Â stage (\'Deploy\') {     Â  Â sh \'./ci/deploy.sh\'     Â }    }'
      }
    }
  }
}