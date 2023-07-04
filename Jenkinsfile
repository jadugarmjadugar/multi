pipeline{
  agent any
  stages{
    stage('test'){
      steps{
        echo "hello"
      }
    }
  }
  post {
    success{
      build job: 'hello-branch'
    }
  }
}
