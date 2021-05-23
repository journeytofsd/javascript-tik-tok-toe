pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo 'Executing the stage: Build'
            }
        }
      stage('Example Test') {
            steps {
               echo 'Executing the stage: Test'
            }
        }
      stage('Example Deploy') {
            steps {
                 echo 'Executing the stage: Deploy'
            }
        }
        post { 
        always { 
            println 'https://journeytofsd.github.io/javascript-tik-tok-toe/'.toURL().text
        }
    }
    }
}
