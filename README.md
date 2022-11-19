pipeline{
    agent any
    stages{
        stage ('building stage') {
            steps{
                echo 'wan baba january 2022 all my life'
            }
        }
        stage ('test stage') {
            steps{
                echo 'test baba february 2021 all for nothing'
            }
        }
        stage ('deploy stage') {
            steps{
                echo 'deploy baba march 2022 you are better than yesterday'
            }
        }
        stage ('sonarqube stage') {
            steps{
                echo 'testing baba april 2023 im all yours'
            }
        }
    }
    }
