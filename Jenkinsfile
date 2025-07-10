pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello, World-feature!'
                echo 'This is another simple message in the Hello stage.'
            }
        }
        stage('More Simple Steps') {
            steps {
                echo 'Now in a new stage!'
                sh 'ls -l'
            }
        }
    }
}
