pipeline{

    agent any
    stages{
        stage('Build'){
            steps {
                // sh 'npm install'
                sh 'npm install'

            }
        }
        stage('test'){
            steps {
                sh 'echo "Testing the application"'
            }
        }
        stage('deploy'){
            steps {
                sh 'echo "deploying the application"'
            }

        }
    }
}