pipeline {
    agent any

    stages {
        stage('Verify Branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
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
            }
        }
        stage('Add New Stage') {
            steps {
                echo 'Beer++'
            }
        }
    }
}