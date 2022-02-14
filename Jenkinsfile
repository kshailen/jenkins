pipeline {
      agent any
              stages {
                    stage("Build") {
                      steps {
                          sh 'echo "Building App" '

                       }
             }
                    stage("Test") {
                                   steps {
                                       sh 'echo "Testing App" '

                                    }
                          }
                    stage("Deploy") {
                                   steps {
                                       sh 'echo "Deploying App" '
                                       script {
                                                println( "Deployed - Printing from groovy Code")
                                       }

                                    }
                          }
      }
    }
