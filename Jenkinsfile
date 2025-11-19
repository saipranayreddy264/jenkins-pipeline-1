pipeline {
    // agent any

    agnet {
        label 'java-slave'
    }
    stages {
        stage ('hostaname') {
            steps {
                sh 'hostname -i'
            }
        }
    }
}
