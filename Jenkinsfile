pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        archiveArtifacts(artifacts: 'login', allowEmptyArchive: true, caseSensitive: true, defaultExcludes: true)
      }
    }

  }
}