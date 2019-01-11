pipeline {
    agent {
      label "builder-aws-cdk"
    }
    stages {
      stage('cdk deploy') {
        steps {
          container('nodejs') {
            sh "cdk deploy"
          }
}
}
}
}
