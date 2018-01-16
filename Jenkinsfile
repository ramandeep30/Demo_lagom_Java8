node {
stage('Initialization') {
  checkout scm
}
  
stage('Maven') {
withEnv(["PATH+MAVEN=${tool 'm3'}/bin"]) {
    sh "mvn clean verify"
}
}
}
