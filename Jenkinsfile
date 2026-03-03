pipeline {
  agent any

  stages {

    stage('Clone') {
      Steps {
        git url: 'https://github.com/guru1raj/Jenkins.simple-demo.git',
          branch:'main'
      }
    }

    stage('Run Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}

          
