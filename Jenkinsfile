pipeline {
    agent any
    stages {
        stage ("Env Varaiable") {
            steps {
                echo "The build number is ${env.BUILD_NUMBER}"
                echo "You can also see \${BUILD_NUMBER -> $BUILD_NUMBER}"
                sh 'echo "I can access $BUILD_NUMBER in shell command as well'
            }
        }
    }
}