pipeline {
    agent { docker { image 'python:3.7'}}
    stages{
        stage('1-Build'){
            steps {
                echo "Start Build"
                echo "Building..."
                sh "python --version"
                echo "End of Build"
            }
        }
        stage('2-Test'){
                echo "Start TEST"
                echo "Testing..."
                echo "End of Build"
            }
        }
        stage('3-Deploy'){
            steps {
                echo "Start Deploy"
                echo "Deploying..."
                echo "End of Deploy"
            }
        }
        stage('4-END'){
            steps {
                echo "Success"
            }
        }
    }
}