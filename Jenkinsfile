node{
    git branch: 'main', url: 'https://github.com/emadlearngit15/jenkins.git'
    stage('Build') {
        try {
            sh 'echo "Building the project..."'
            catch (Exception e) {
                echo "Build failed: ${e.message}"
                error "Stopping the pipeline due to build failure."
                throw e
        }

    }
    stage('Test') {
        try {
            sh 'echo "Running tests..."'
            catch (Exception e) {
                echo "Tests failed: ${e.message}"
                error "Stopping the pipeline due to test failure."
                throw e
        }

    }
}
