node {
    git branch: 'main', url: 'https://github.com/emadlearngit15/jenkins.git'

    stage('build') {
        try {
            sh 'echo "build stage"'
        }
        catch(Exception e) {
            sh 'echo "exception found"'
            throw e
        }
    }

    stage('test') {
        sh 'echo "test stage"'
    }
}
