node {
  stage('clean') {
    sh 'pwd'
    sh 'ls -al'
    sh './gradlew wrapper'
    sh "./gradlew clean"
  }
  stage('build') {
    sh "./gradlew build"
  }
  stage('test') {
    sh "./gradlew test"
  }
}
