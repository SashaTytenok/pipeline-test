properties([disableConcurrentBuilds()])
pipeline {
    agent {
        label 'master'
    }
    options{
    timestamp()
    }
    stages {
        stage('step 1') {
            steps {
                echo 'Building..'
                docker run hello-world
            }
        }
    }
}
