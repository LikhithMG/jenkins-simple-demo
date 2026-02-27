pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git url: 'https://github.com/LikhithMG/jenkins-simple-demo.git', branch: 'main'
            }
        }

        stage('Run Script') {
            steps {
                sh 'echo "Running script..."'
                // Replace with your actual script
                // sh 'bash script.sh'
            }
        }
    }
}
