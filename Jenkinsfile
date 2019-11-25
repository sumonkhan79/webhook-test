pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo "This is the first stage"
                echo "first one dude"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                echo "This is the 2nd stage"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                echo "this is the 3rd and also the final stage"
            }
        }
    }
}
