pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "test3"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
