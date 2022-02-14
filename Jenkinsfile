pipeline {
    agent any
    environment {
        PIPELINE_TYPE = "Multi Branch Pipeline"
        ENVIRONMENT_VERSION = "1.0.4"


    }
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
                                                println "Deploying ${ENVIRONMENT_VERSION}"
                                       }

                                    }
                          }
                    stage("Post Deployment"){
                        steps {
                            echo "Post Deployment Steps"
                            script {
                                println( "Post deployment Sanity")
                            }

                        }
                    }


      }
    }
