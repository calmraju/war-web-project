pipeline {
    agent any
    
    stages {
        stage('Git clone') {
            steps {
                git url:'https://github.com/calmraju/war-web-project.git', branch :'master'
            }
        }
        stage('build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
   
}
