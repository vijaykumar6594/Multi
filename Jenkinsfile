pipeline{
  agent any
  stages{
    stage("Hello Leo"){
      steps{
        echo "Hello Leo"
      }
    }
  }
  post{
    success{
      mail bcc:'',body:'Hello Leo...! This build is success',cc:'',replyTo:'',subject:'Jenkins || Build',to:'bandivijaykumarbvk@gmail.com'
}
