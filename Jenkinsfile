pipeline {
    agent any
    environment {
        branch_name = 'feature'
    }
    stages {
        stage ('this is when example') {
                when {
                    environment name: 'branch_name', value: 'feature'
                }
                steps {
                echo "feature branch is executed"
                }

            }
        }
    }
