pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                // Checkout the repository
                git branch: 'main', url: 'https://github.com/HanaATawfik/jenkins-pipeline-demo-20216116.git'
            }
        }
        stage('Run Script') {
            steps {
                // Execute the script
                sh './script.sh'
            }
        }
    }
}
