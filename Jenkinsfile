pipeline {
      agent any
      stages {
          stage('build') {
              steps {
                 sh 'go build hello-world.go'
              }
          }
          stage('test') {
               steps {
                  sh 'go run hello-world.go'
              }
          }
      }
}
