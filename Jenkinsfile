pipeline {
    agent any

    triggers {
        githubPush() // Очікує пуши з GitHub
    }

    stages {
        stage('Hello world') {
            steps {
                echo 'Hello world!'
            }
        }
    }
}


