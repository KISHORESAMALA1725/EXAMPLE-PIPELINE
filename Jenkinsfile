pipeline {
    agent any
    environment {
        branch_name = 'feature'
    }
    stages {
        stage ('this is when example') {
            steps {
                when {
                    environment name: "branch_name", value= "feature"
                }
                echo "feature branch is executed"
            }
        }
    }
}
