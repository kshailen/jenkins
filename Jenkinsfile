pipeline {
      agent any
              stages {
                    stage("Build") {
                      steps {
                          echo "Building App"

                       }
             }
                    stage("Test") {
                                   steps {
                                       echo "Testing App"

                                    }
                          }
                    stage("Deploy") {
                                   steps {
                                       echo "Deploying App"
                                       script {
                                                println( "Deployed - Printing from groovy Code")
                                       }

                                    }
                          }
      }
    }
