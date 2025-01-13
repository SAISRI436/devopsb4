/*pipeline{
    agent any
    stages{
        stage('stage1'){
            steps{
                echo"Hello World"
            }
        }
        stage('stage2'){
            steps{
                echo"Welocme to Jenkins pipeline"
            }
        }
    }
}*/

pipeline{
    agent{
        label 'java-agent-slave'
    }
    stages{
        stage('first stage'){
            steps{
                echo("Execute this stage")
            }
        }
    }
}
