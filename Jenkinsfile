pipeline {
    agent any
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
     stage('Example Deploy') {
            steps {
                 sh 'start https://journeytofsd.github.io/javascript-tik-tok-toe/'
            }
        }
}
