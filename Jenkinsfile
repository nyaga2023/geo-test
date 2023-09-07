pipeline{
    agent any
    stages{
    stage('maven clean'){
            steps{
               sh 'mvn clean' 
            }
        }
    stage('maven install'){
        steps{
            sh 'maven install'
            sh 'echo hi'
        }
    }
 stage('maven package'){
        steps{
            sh 'maven package'
        }
    }
    }

}