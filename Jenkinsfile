pipeline {
    agent any

    stages {
        stage ('Clean Stage') {

            steps {
                withMaven(maven : 'apache-maven-3.6.3') {
                    bat 'mvn clean install'
                }
            }
        }

        stage ('Package Stage') {

            steps {
                echo 'Hello'
            }
        }


      
    }
}
