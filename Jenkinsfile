pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "hola atodos"
            }
        }
        when {
            expression {
                BRANCH_NAME == 'FACU'
            }
        }
        stage('test') {
            steps {
                echo 'Testeando'
            }
        }
        
    }
}