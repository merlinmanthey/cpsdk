pipeline {
  agent any
  stages {
    stage('') {
      steps {
        cmakeBuild(buildDir: 'build', buildType: 'debug', installation: '"InSearchPath"', generator: 'Makefile', sourceDir: '.')
      }
    }

  }
}