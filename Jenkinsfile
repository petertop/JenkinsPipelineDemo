pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello Jenkins!!!!????'
            }
        }
        stage('Check branch and build') {
            steps {
                echo "Build number: ${env.BUILD_NUMBER}"
                echo "Git branch: ${env.GIT_BRANCH}"
                echo "${env.GIT_BRANCH}"
            }
        }
        stage('Goodbye') {
            steps {
                echo 'Goodbye World'
                echo 'Hello from Visual Studio'
                echo 'Hello from Visual Studio once more'
            }
        }
    }
}