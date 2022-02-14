# jenkins
Jenkins files can be written in two formats.
##Scripted:
groovy script </br>
groovy engine </br>
Advanced scripting capabilities , high flexibility </br>


```
node {
 //groovy script
}
```
##Declerative Pipeline:

```
    pipeline {
      agent any
              stages {
                    stage("Stage_name") {
                      steps {
                          sh 'echo "Sample pipeline" '

                       }
             }
      }
    }
    
```







Notes:

https://www.youtube.com/watch?v=7KCS70sCoK0&list=PLy7NrYWoggjw_LIiDK1LXdNN82uYuuuiC&index=6

https://www.dltlabs.com/blog/how-to-create-a-jenkins-declarative-pipeline-348445
