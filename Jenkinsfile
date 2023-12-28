pipeline {
  
    agent  any
    
    tools{
        maven "maven"
    }

    stages {
        stage('Clone') {
            steps {
              git 'https://github.com/sanketh0107/maven-web-app.git'
            }
        }
    }
}
        
