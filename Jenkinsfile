pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "nu ga ik alles effen builden"
				sh './gradlew --no-deamon'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}