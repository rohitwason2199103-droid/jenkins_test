pipeline {
    agent any // Designates where the pipeline will run
    string(name: 'MESSAGE', defaultValue: 'Hello', description: 'A message to display')
    stages {
        stage('Example Print Stage') {
            steps {
               sh "echo \"${params.MESSAGE}\""
                echo "${MESSAGE}"
            }
        }
    }
}
