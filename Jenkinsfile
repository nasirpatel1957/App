@Library ('SHARED_LIBRARY') _
pipeline {
    agent any
    
    stages {
       
        stage ("1. Git Checkout") {
            steps {
                    GitCheckout (
                        branch: 'main',
                        url: 'https://github.com/nasirpatel1957/App.git'
                    )

                }
            }
        }


    }
