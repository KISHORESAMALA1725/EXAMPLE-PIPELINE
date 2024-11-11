pipeline {
    agent any
    environment {
        BRANCH_NAME = 'feature'
    }
    stages {
        stage ('this is when example') {
                when {
                    environment name: 'BRANCH_NAME', value: 'feature'
                }
                steps {
                echo "feature branch is executed"
                }

            }
        }
    }
