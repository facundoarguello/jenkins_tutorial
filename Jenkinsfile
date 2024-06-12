pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "hola atodos"
            }
        }
        
        stage('test') {
            when {
                expression {
                    BRANCH_NAME == 'FACU'
                }
            }
            steps {
                echo 'Testeando'
            }
        }
        
    }
}