pipeline {
    agent {
        label 'java-slave'
    }
    stages {
        stage ('Build') {
            steps {
                timeout (time: 5, unit: 'SECONDS') // alues: NANOSECONDS, MICROSECONDS, MILLISECONDS, SECONDS, MINUTES, HOURS, DAYS
                {
                    echo "Sleeping for 60 Seconds"
                    sleep 60
                    // siva input ====. yes | no
                }

            }
        }
    }
}
