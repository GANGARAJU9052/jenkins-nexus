pipeline {
    agent any
    tools {
        maven "MAVEN"
    }
    
    stages {
        
        stage("Build Maven") {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteconfigs: [[credentialId: GIT_REPO', url: 'https://github.com/GANGARAJU9052/jenkins-nexus';
                
                sh "mvn -Dmaven.test.failure.ignore=true clean package"                                                                                                
            }
        }
    }                                                                                                          
}
