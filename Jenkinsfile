pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo Building...'
                sh 'chmod +x hello-world.sh'
            }
        }
        stage('test') {
            steps {
                sh 'echo Testing...'
            }
        }
        stage('run') {
            steps {
                sh 'echo Running...'
                sh './hello-world.sh'
            }
        }
    }
}
