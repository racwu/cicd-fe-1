pipeline {
  agent any
  stages {
    stage('Build'){
      steps{
        echo "Make executable"
        chmod +x helloworld.sh
      }
    }
    stage('Test'){
      steps{
        echo "Check contents"
        cat helloworld.sh
      }
    }
    stage('Deploy'){
      steps{
        "Run"
        ./helloworld.sh
      }
    }
  }
}
