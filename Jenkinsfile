pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        bat 'echo Hi, this is Anshul from LevelUp360'
                        bat 'echo We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        bat 'echo Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        bat "echo Deploying in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        bat "echo Deploying in Production Area"
                  }
            }
      }
}