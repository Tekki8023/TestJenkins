pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "master"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
