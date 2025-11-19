pipeline {
    // agent any

    agent {
        label 'java-slave'
    }
    stages {
        stage ('hostaname') {
            steps {
                sh 'hostname -i'
            }

        stage ('secondstage') {
            steps {
                echo "welcome to new pipelines"
            }
        }
        }
    }
}
