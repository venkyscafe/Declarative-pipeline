pipeline {
    agent any
    stages {
        stage ('SCM') {
            steps {
                git branch: 'main', url: 'https://github.com/venkyscafe/Declarative-pipeline.git'
            }
        }
    }
}