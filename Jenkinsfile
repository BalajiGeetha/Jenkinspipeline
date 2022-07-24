pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
              git branch: 'main', credentialsId: 'MyGitHub', url: 'https://github.com/BalajiGeetha/Jenkinspipeline'
            }
        }
    }
}

