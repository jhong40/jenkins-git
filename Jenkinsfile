pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World 555"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
