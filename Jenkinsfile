pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh "./gradlew compileJava"
            }
        }

        stage('Unit Test') {
            steps {
                echo 'Tesing stage ... '
            }
        }
    }

}
