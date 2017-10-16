pipeline {
    agent none
    stages{
        stage("Build"){
            agent master
            steps {
                echo "Building..."
                sh 'sleep 5'
            }
        }

        stage("Test"){
            agent node1
            steps {
                echo "Testing..."
                sh 'sleep 5'
            }
        }
    }


}
