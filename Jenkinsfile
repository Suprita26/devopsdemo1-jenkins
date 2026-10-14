pipeline{
  agents any{
    stages{
      steps('complie')
      {
        bat "javac hello.java"
      }
      steps('run')
      {
        bat "java hello"
      }
    }
  }
}
