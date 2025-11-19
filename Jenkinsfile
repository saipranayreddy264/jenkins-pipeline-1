pipeline {
    agent {
        label 'java-slave'
    }

    stages {
        stage ('build') {
            steps {
                echo "This is a build stage"
            }
        }
        stage ('groovycodestage') {
            steps {
                script {
                    // define a variable
                    def course ="k8s"

                    // if condition
                    if (course == "k8s")
                    println("Thanks for enrolling to k8s")
                    else
                    println("Do enroll for k8s")
                }
            }
        }
    }
}
