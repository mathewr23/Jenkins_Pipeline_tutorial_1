pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh 'echo "Your name is" && whoami'
                sh '''
                    echo "Multiline shell steps works too"
                    echo "Your present working directory is: "
                    pwd
                    echo "These are the items in your present working directory: "
                    ls -lap
                '''
            }
        }
    }
}
