pipeline{
    agent {node {label 'agent1'}}
    options{
        timeout(time: 1, unit: 'HOURS')
        ansiColor('xterm')
    }
    stages{
        stage('install npm dependencies')
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