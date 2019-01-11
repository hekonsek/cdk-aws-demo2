pipeline {
    agent {
      label "builder-aws-cdk"
    }
    stages {
      stage('cdk deploy') {
        steps {
          container('foo') {
            sh "cdk deploy"
          }
}
}
}
}
