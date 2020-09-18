properties([disableConcurrentBuilds()])
pipeline {
    agent {
        docker { image 'hello-world' }
    }
    options{
    timestamp()
    }
    stages {
        stage('step 1') {
            steps {
                echo 'Building..'
            }
        }
    }
}
