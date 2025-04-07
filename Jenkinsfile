pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Original (wrong for Windows)
                // sh 'mvn clean install'
                
                // Correct (for Windows)
                bat 'mvn clean install'
            }
        }
    }
}
