pipeline{
  agent any
  stages{
    stage("Deploy"){
      steps{
        echo "Test sucessful"
        bat"mvn compile"
      }
    }
        stage("Build"){
      steps{
        echo "Build sucessful"
        bat"mvn clean"
      }
    }
        stage("Test"){
      steps{
        echo "Test sucessful"
        bat"mvn test"
      }
    }
  }
