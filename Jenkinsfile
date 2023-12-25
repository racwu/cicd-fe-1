pipeline {
  agent any
  stages {
    stage('Build'){
      steps{
        echo "Make executable"
        sh 'chmod +x helloworld.sh'
      }
    }
    stage('Test'){
      steps{
        echo "Check contents"
        sh 'cat helloworld.sh'
      }
    }
    stage('Deploy'){
      steps{
        echo "Run"
        sh './helloworld.sh'
      }
    }
  }
}
