pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
         stage('Building') {
            steps {
                echo 'Building...'
                cmake CMakeLists.txt
            }
        }
    }
}
