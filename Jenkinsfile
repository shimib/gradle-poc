timestamps {
    node {
        stage('Checkout') {
            checkout scm
        }

        stage('Build') {
            sh "./gradlew build"
        }
    }
}