pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "test2"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
