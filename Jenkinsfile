pipeline {
    agent any
    tools {
        maven 'MAVEN_HOME'
    }
    stages {
        stage("build") {
            steps {
            bat 'mvn clean install'
            }
        }
    }
}