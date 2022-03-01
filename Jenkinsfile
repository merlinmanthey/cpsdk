pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        cmakeBuild(buildDir: 'build', buildType: 'debug', installation: 'CMakeDefault', generator: 'Unix Makefiles', sourceDir: '.')
      }
    }

  }
}