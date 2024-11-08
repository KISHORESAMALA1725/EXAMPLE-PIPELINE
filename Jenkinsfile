pipeline {
    agent any
    stages {
        stage ('BRANCH_EXECUTION') {
            when {
                expression {
                    branch_name ==~ /(feature|hotfix)/
                }
            }
            steps {
                echo "Required HOTFIX branch got executed"
            }
        }
    }
}
