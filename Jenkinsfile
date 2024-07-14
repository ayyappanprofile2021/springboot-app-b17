pipeline {
    agent { Label 'Agent1' }

    stages {
        stage('Cloning') {
            steps {
                git branch: 'main', url: 'https://github.com/ayyappanprofile2021/springboot-app-b17.git'
            }
        }

	stage('Packagin') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
