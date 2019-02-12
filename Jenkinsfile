#!groovy

forkedRepositorySshUrl = "https://github.com/549393092/test002.git"
    
stage('Commit') {
    node {
        deleteDir()
        git url: forkedRepositorySshUrl
    }
}
