pipeline{
    agent {node {label 'agent1'}}
    options{
        timeout(time:1, unit:'Hours')
        ansiColor('xterm')
    }
    stages{
        stage('install dependencies')
        {
            steps{
                sh '''
                  npm install
                '''
            }
        }
       stage ('unit testing') {
        steps{
            echo "unit tetsing"
        }
       }
    }
}