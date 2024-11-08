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
                echo "Required feature branch got executed"
            }
        }
        stage {
            steps {
                echo "***** THIS STAGE IS SKIPPED !!!!! *****"
            }
        }
    }
}
