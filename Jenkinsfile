node {
  stage('clean') {
    pwd
    ls -al
    sh "./gradlew clean"
  }
  stage('build') {
    sh "./gradlew build"
  }
  stage('test') {
    sh "./gradlew test"
  }
}
