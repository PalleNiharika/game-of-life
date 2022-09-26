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
                agent{label 'OPENJDK-11-MVN'}
                git url: 'https://github.com/PalleNiharika/game-of-life.git', 
                    branch: 'brach_1'
            }
        }
    }
}
