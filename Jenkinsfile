pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'We will list current dir'
                sh "ls ."
            }

            post {
                success {
                    echo "pipeline run successfully"
                }
            }
        }
    }
}
