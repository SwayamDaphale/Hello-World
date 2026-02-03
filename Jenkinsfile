pipeline {
    agent any (1)
    stages {
        stage('Build') { (2)
            steps {
                echo "In Build stage."
            }
        }
        stage('Test') { (4)
            steps {
                echo "In test stage."
            }
        }
        stage('Deploy') { (6)
            steps {
                echo "In Deploy stage."
            }
        }
    }
}
