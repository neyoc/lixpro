pipeline {
    agent any 
    stages {
        stage('--clean---') { 
            steps {
                echo "Hello World!"
                sh "echo Hello from the shell"
                sh "hostname"
                sh "uptime" 
            }
        }
        stage('Test') { 
            steps {
                echo "Hello World MATE!"
                sh "echo Hello from the shell"
                sh "hostname"
                sh "uptime" 
            }
        }
        stage('--package--') { 
            steps {
                echo "Hello World package!"
                sh "echo Hello from the shell"
                sh "hostname"
                sh "uptime"
            }
        }
    }
}
