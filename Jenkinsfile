pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh 'echo hello'
            }
        }
        stage('learning') {
            steps {
                git url: 'https://github.com/GitPracticeRepo/game-of-life.git', 
                    branch: 'master'
            }
        }
    }
}
