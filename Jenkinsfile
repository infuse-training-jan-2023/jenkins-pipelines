pipeline {
    agent {label "jenkins-slave-harish"}
    triggers {
        cron('H H * * 1-5')
    }
    stages {
        stage('build') {
            steps {
                echo env.STAGE_NAME
            }
        }
        stage('test') {
            steps {
                echo env.STAGE_NAME
            }
        }
    }
}
