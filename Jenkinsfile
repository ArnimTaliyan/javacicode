pipeline {

    agent any

    stages {
        stage('GIT Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/ArnimTaliyan/javacicode.git'
            }
        }
        stage('UNIT TESTING') {
            steps {
                sh 'mvn test'
            }
        }
    }
}