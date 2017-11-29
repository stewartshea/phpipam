node('nodejs') {
  stage('build') {
    openshiftBuild(buildConfig: 'phpipam')
  }
  stage('deploy') {
    openshiftDeploy(deploymentConfig: 'phpipam')
  }
}
