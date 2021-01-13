pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                dir('test1') {
                    git branch: dev, url: 'https://github.com/rvemulapati/multibranchjenkins.git', credentialsId: 'vemulapatirohini@gmail.com'
                }
                sh('build_process')
            }
        }
    }
}
