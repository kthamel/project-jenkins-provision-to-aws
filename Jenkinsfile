pipilie {
    agent any
    stages {
        stage('stage_1') {
            steps {
                echo "Hello World"
            }
        }
        state('stage_2') {
            steps {
                withGroovy {
                    echo "pipeline url was ${env.JENKINS_URL}"
                }
            }
        }
    }
}