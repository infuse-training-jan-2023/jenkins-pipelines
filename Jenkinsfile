pipeline {
     agent {
        label 'slave1'
    }

    stages {
        stage('build') {
            steps {
                echo '${env.STAGE_NAME}'
            }
        }
        stage('test') {
            steps {
                echo '${env.STAGE_NAME}'
            }
        }
    }
}
