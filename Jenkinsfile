

pipeline {
    agent any
    stages {
        stage('build') {
            agent any
            steps {
                script {
                    showMavenVersion('mvn version')
                }
            }
        }
    }
}

def showMavenVersion(String a) {
        bat 'mvn -v'
        echo a
}