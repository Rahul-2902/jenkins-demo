pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Run Script') {
            steps {
                sh 'bash app.sh'
            }
        }
    }
}
