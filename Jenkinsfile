def x = "hello"
String y = "World"

pipeline {
    agent any
    stages {
        stage('build') {
            agent any
            steps {
                script {
                    echo x
                    echo y
                    showMavenVersion('mvn version')
                }
            }
        }
    }
}

def showMavenVersion(String a) {
        echo "Hello ${a}"
}

