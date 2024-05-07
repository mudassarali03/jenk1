pipeline{

    agent any
    stages{
        stage('Build'){
            steps {
                // sh 'npm install'
                bat 'npm install'

            }
        }
        stage('test'){
            steps {
                bat 'echo "Testing the application"'
            }
        }
        stage('deploy'){
            steps {
                bat 'echo "deploying the application"'
            }

        }
    }
}