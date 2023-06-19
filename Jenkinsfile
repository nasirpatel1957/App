pipeline {
    agent any
    
    stages {
       
        stage ("1. Git Checkout") {
            steps {
                script {
                    GitCheckout (
                        branch: 'main',
                        url: 'https://github.com/nasirpatel1957/App.git'
                    )

                }
            }
        }


    }
}