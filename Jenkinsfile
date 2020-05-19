pipeline {
    agent any
    
    stages {
        
        stage('build') {
            steps {
                echo 'Hello World'
                echo "${BUILD_ID}"
            }
        }
        
        stage('build2') {
            steps {
                echo 'Hello other'
                bat 'set'
            }
        }
        
    }
}
