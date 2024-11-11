pipeline {
    agent any
    stages {
        stage('this is expression stage') {
            steps {
               when {
                  expression {
                    branch_name ==~ /(feature|hotfix)/
                  }
               }
               echo "this branch is executed"
            }
        }
    }
}
