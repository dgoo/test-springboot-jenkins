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
        currentBuild.result = 'FAILURE'
        println 'Deploy Skip'
    }
        sh "echo 'Deply AWS'"
    }
}