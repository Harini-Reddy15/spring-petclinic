pipeline {
    agent any
   
    stages {
        stage('Git-clone') {
            steps {
                git branch: 'main', url: 'https://github.com/Harini-Reddy15/spring-petclinic.git'
            }
        }
        stage('Hello') {
            steps {
                sh '''mvn package
'''
            }
        }
    }
}
