pipeline {

    agent any

    stages {

        stage('Test Git') {

            steps {
                sh 'git --version'
            }
    }
        stage('Test Docker') {
            steps {
                sh 'docker --version'
            }
        }


    }
}




