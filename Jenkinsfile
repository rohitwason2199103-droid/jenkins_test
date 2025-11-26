pipeline {
    agent any // Designates where the pipeline will run
     parameters {
    string(name: 'MESSAGE', defaultValue: 'Hello', description: 'A message to display')
     }
    stages {
        stage('Example Print Stage') {
            steps {
               echo "The value of myParameter is: ${params.MESSAGE}"

            }
        }
    }
}
