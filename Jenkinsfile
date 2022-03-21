pipeline {
    agent {label 'dev'}

    stages {
        stage('Checkout') {
            steps {
                git branch: 'develop', url: 'https://github.com/chia5/Jenkins_Assign.git'
            }
        }
    }
}
