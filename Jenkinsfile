pipeline {
    agent any
    stages {
        stage ('STAGE1') {
            steps {
                echo "The git commit id or hash is :${GIT_COMMIT}"
                echo "${GIT_PREVIOUS_COMMIT}"
                echo "${GIT_BRANCH}"
                echo "${GIT_URL}"
}
}
}
}
