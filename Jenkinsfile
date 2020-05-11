@Library('my-jenkins-library@master') _
pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            gitCheckout(
                branch: "master",
                url: "https://github.com/jchaudhu/python-cicd.git"
            )
            }
    }
    }
}
