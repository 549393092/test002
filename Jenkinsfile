#!groovy
    
stage('Commit') {
    node {
        deleteDir()
        checkout scm
        sh 'mvn -B clean verify'
    }
}
