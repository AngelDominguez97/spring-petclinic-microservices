pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                //Cambio para que funcione el repo de docker de angel
                sh 'mvn clean install -PbuildDocker'
            }
        }
    }
}
