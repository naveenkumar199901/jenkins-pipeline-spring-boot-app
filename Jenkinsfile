pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                echo 'build stage completed'
            }
        }
	stage('test') {
            steps {
                echo 'test stage completed'
            }
        }
	stage('publish') {
            steps {
                echo 'publish stage completed'
            }
        }
    }
}