pipeline {
    agent any

    // tools {
    //     maven 'your-maven-tool-name' // Use the Maven installation name from step 2
    // }

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/DhariniMansi/task-4.git'
            }
        }

        stage('Build') {
            steps {
                script {
                    sh 'mvn clean install'
                }
            }
        }


    }

   
    }

