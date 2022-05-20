pipeline {
    agent any
    tools {
        maven "MAVEN"
    }
    
    stages {
        
        stage("Build Maven") {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteconfigs: [[credentialId: 'git_credentials1',  url: 'https://github.com/GANGARAJU9052/jenkins-nexus.git';]
                
                sh "mvn -Dmaven.test.failure.ignore=true clean package"                                                                                                
            }
        }
    }                                                                                                          
}
