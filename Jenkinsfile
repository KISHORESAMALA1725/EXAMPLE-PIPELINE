pipeline {
    agent any
    environment {
        HOTFIX_BRANCH = 'hotfix'
        FEATURE_BRANCH = 'feature'        
    }
    stages {
        stage ('BRANCH_EXECUTION') {
            when {
                expression {
                    environment name: HOTFIX_BRANCH, value: 'hotfix'
                }
            }
            steps {
                echo "Required HOTFIX branch got executed"
            }
        }
    }
}
