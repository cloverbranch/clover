pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello feature1...'
		echo "changes on $GIT_BRANCH with commit message: ${GIT_COMMIT_MSG}"
            }
        }
    }
}

