pipeline{
    agent any
    
    environment{
        PATH=/"opt/maven3/bin:$PATH"
    }     
    stages{
        stage('declarative pipeline'){
            steps{
                git 'https://github.com/Narendra-devops/python-app.git'
            }
        }
        stage('maven build'){
            steps{
                sh "mven clean package"
            }
        }
    }
}
    
