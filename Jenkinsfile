pipeline{
  agents any{
    stages{
      steps('complie')
      {
        bat "javac Hello.java"
      }
      steps('run')
      {
        bat "java Hello"
      }
    }
  }
}
