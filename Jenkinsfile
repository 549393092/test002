#!groovy
    
stage("build & SonarQube analysis") {
    node {
        deleteDir()
        checkout scm
        withSonarQubeEnv('SonarQube') {
           sh 'mvn clean package sonar:sonar'
        }
    }
}
