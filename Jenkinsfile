pipeline {
    agent any
    stages {
        stage('carga'){
            steps {
               sh "mvn verify -Pperformance" 
            }

        }
    }    

}