pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello New World'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}