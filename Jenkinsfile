pipeline {
    agent any

    stages {
        stage('TAHA') {
            steps {
                  sh '''
                  touch test.txt
                  echo 'by Taha '
                  echo 'Hello World' > test.txt
                  pwd
                  ls -l
                  '''
            }
        }
    }
}