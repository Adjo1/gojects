pipeline{
    agent any
    stages{
        stage('initialisation'){
            steps{
                echo 'initialisation'
                sh 'jenkins --version'
            }
        }
        stage('build'){
            steps{
                echo'the building'
                 sh 'docker build -t exemple:${BUILD_ID} .'
            }
        }
        stage('test'){
            steps{
                echo'the testing'
            }
        }
        stage('deploy'){
            steps{
                echo 'the deploy'
            }
        }
    }
}
