pipeline{
    agent any
    stages{
    stage('maven clean'){
            steps{
               mvn clean 
            }
        }
    stage('maven install'){
        steps{
            mvn install
            sh 'echo hi'
        }
    }
 stage('maven package'){
        steps{
            mvn package
        }
    }
    }

}