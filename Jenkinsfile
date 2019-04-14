node {
    stage('Ready') {
        sh "echo 'Ready'"
    }

    stage('Build') {
        sh './gradlew clean print'
        sh "echo 'Build Jar'"
    }

    stage('Deploy') {
    try {
        input('ㅂㅐ포하나욤??')
        println 'Deploy Start'
    } catch (Exception e) {
        error('Deploy is aborted by the user')
        println 'Deploy Skip'
    }
        sh "echo 'Deply AWS'"
    }
}