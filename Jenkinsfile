pipeline{
    agent any
    stages{
        stage('Build-1'){
            steps{
                echo "Building Stage ..!"
            }
        }
        stage('Build-2'){
            steps{
                echo "Building 2 nd Stage ..!"
                sh 'sleep 5'
            }
        }
    }
}