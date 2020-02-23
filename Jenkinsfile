pipeline {
  agent any
  stages {
    stage('message') {
      steps {
        sh 'echo "testing Blue ocean"'
      }
    }

    stage('well give it a try') {
      parallel {
        stage('well give it a try') {
          steps {
            sh 'echo "well let give a try"'
          }
        }

        stage('clear blue') {
          steps {
            mail(subject: 'build done', body: 'cool build', from: 'sauravpatar95@gmail.com', to: 'saurav@teqfocus.com')
          }
        }

      }
    }

  }
}