pipeline{
    agent any
    stages{
        stage('Build-1'){
            step{
                echo "Building Stage ..!"
            }
        }
        stage('Build-2'){
            step{
                echo "Building 2 nd Stage ..!"
                sh 'sleep 5'
            }
        }
    }
}