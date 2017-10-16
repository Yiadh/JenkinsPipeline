pipeline {
    agent none
    stages{
        stage("Build"){
            agent {
		label: master
	    }
            steps {
                echo "Building..."
                sh 'sleep 5'
            }
        }

        stage("Test"){
            agent {
		label: node1
	    }
            steps {
                echo "Testing..."
                sh 'sleep 5'
            }
        }
    }


}
