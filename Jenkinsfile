node {
  stage('clean') {
    sh "./gradlew clean"
  }
  stage('build') {
    sh "./gradlew build"
  }
  stage('test') {
    sh "./gradlew test"
  }
}
