node {
    stage('Ready') {
        sh "echo 'Ready'"
    }

    stage('Build') {
        sh './gradlew clean print'
        sh "echo 'Build Jar'"
    }

    stage('Deploy') {
        sh "echo 'Deply AWS'"
    }
}