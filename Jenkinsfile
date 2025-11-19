pipeline {
    agent {
        label ('java-slave')
    }

    stages {
        stage ('build stage') {
            steps {
                echo "This is a build stage"
                error "this is a failure"
            }
        }
        stage ('scans') {
            steps {
                echo "Executing sonar scans....."
            }
        }
    }
}
