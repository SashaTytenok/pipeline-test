properties([disableConcurrentBuilds()])
pipeline {
    agent {
        label 'master'
    }
    options{
    timestamps()
    }
    stages {
        stage('step 1') {
            steps {
                echo 'Building..'
                sh 'docker run hello-world'
            }
        }
    }
}
