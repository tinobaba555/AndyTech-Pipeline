pipeline{
    agent any
    stages{
        stage ('building stage') {
            steps{
                echo 'wan baba january 2020'
            }
        }
        stage ('test stage') {
            steps{
                echo 'test baba february 2021'
            }
        }
        stage ('deploy stage') {
            steps{
                echo 'deploy baba march 2022'
            }
        }
        stage ('sonarqube stage') {
            steps{
                echo 'testing baba april 2023'
            }
        }
    }
    }
