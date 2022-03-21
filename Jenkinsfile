node{
  stage('SCM Checkout'){
    git 'https://github.com/Shashibadiger/pipe.git'  
  }
  stage('compile-package){
        sh "mvn package"
        }
}
