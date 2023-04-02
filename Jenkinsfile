pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Test')
        {
            steps
            {
             echo 'Test App'   
            }
        }
        stage('Deploy')
        {
            steps{
                echo 'Deploy App'
            }
        }
    }
    post{
        always{
            emailext body: '', subject: 'PipeLine Status', to: 'clubcricketfan9@gmail.com'
        }
    }
}
