pipeline {
    agent any

    stages {
        stage ('Clean Stage') {

            steps {
                withMaven(maven : 'M2_HOME') {
                    bat 'mvn clean install'
                }
            }
        }

      


      
    }
}
