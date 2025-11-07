 pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main', url: 'https://github.com/pavanbharati/pythonhelloworld.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                script {
                    dockerImage = docker.build('python-hello-world')
                    echo 'Docker Image build suceesfull'
                }
            }
        }

        stage('Run Container') {
            steps {
                script {
                    dockerImage.run()
                    echo 'Container created'
	
	 stage('Updated by Kaustubh') {
            steps {
                script {
                    echo 'updated by Kaustubh'
                }
            }
        }	
                }
            }
        }
    }
}
