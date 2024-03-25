pipeline {
    agent any

    stages {
        stage('Main branch') {
            steps {
               sh 'echo "This is main branch"
            }
        }
     
        stage('sprint1') {
            steps {
               sh 'echo "this is sprint1 branch..."
            }
        }i

        stage("Development") {
             steps {
                sh 'echo "Deploying application..."
            }
        }  
    }
}
