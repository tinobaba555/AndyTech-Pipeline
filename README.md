pipeline{
    agent any
    stages{
        stage ('building stage') {
            steps{
                echo 'wan baba'
            }
        }
        stage ('test stage') {
            steps{
                echo 'test baba'
            }
        }
        stage ('deploy stage') {
            steps{
                echo 'deploy baba'
            }
        }
        stage ('sonarqube stage') {
            steps{
                echo 'testing baba'
            }
        }
    }
    }
