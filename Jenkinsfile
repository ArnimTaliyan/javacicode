pipeline {

    agent any

    stages {
        stage('GIT Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/ArnimTaliyan/javacicode.git'
            }
        }
        stages {
        stage('UNIT TEST') {
            steps {
                sh 'mvn test'
    }
}
        }
    }
}