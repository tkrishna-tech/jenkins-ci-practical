pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Jenkins is running the CI pipeline!'
                bat 'type hello.txt'
            }
        }

        stage('Build Success') {
            steps {
                echo 'Build completed successfully!'
            }
        }
    }
}
