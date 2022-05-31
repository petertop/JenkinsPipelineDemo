def DEPL_ENVS=SKB_TARGET_ENVIRONMENTS.split(',') as List
pipeline {
    agent any

    parameters {
    choice( name: 'DEPLOY_TO', choices: DEPL_ENVS, description: 'Target enviroment')
  }

    stages {
        stage('Verify Branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello Jenkins!!!!????'
                echo 'Selected choice'
                echo "$params.DEPLOY_TO"
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
<<<<<<< HEAD
                echo 'Delete'
=======
            }
        }
        stage('Add New Stage') {
            steps {
                echo 'Beer++'
>>>>>>> development
            }
        }
    }
}