node {
stage('Initialization') {
  checkout scm
}
  
stage('Maven') {
withEnv(["PATH+MAVEN=${tool 'M3'}/bin"]) {
    sh "mvn clean verify"
}
}
}
