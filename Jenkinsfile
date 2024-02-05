pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from your version control system (e.g., Git)
                git branch: 'main', 'https://github.com/santosh10392/mywebpage.git'
                
            }
        }

        stage('Build') {
            steps {
                // Build the project using Maven
                sh 'mvn clean install'
            }
        }
    }
}
