pipeline {
    agent any

    environment {
        // Define environment variables if needed
        MY_VARIABLE = 'Yogi Boy'
    }

    stages {
        stage('Checkout') {
            steps {
                // Checkout source code from version control
                echo 'Checking out'
            }
        }

        stage('Build') {
            steps {
                // Build your application (replace with your build commands)
               echo 'Building'
               echo MY_VARIABLE
            }
        }

        stage('Test') {
            steps {
                // Run tests (replace with your test commands)
              echo 'Testing'
            }
        }

        stage('Deploy') {
            steps {
                // Deploy your application (replace with your deployment commands)
                'echo "Deploying..."'
            }
        }
    }
}
