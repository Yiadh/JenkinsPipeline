pipeline {
    agent master
    stages{
        stage("Build"){
            echo "Building..."
            sh 'sleep 5'
        }
    }

   agent node1
   stages{
        stage("Test"){
            echo "Testing..."
            sh 'sleep 10'
        }
   }

}
