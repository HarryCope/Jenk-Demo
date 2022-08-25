
pipeline {
    agent any
    stages {
      stage('Running Shell Script') {
        steps {
          sh '''
          my_name="Harry"
          echo ${my_name}
          bash ./hello.sh
          '''
          
            }
        }
    }
}
