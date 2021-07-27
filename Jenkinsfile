pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello Jenkins'
            }
        }
        stage('Check branch') {
            steps {
                echo 'Build number: ${env.BUILD_NUMBER}'
                echo 'Git branch ${GIT_BRANCH}'
            }
        }
        stage('Goodbye') {
            steps {
                echo 'Goodbye World'
                echo 'sdfsf'
                echo 'Hello from Visual Studio'
            }
        }
    }
}