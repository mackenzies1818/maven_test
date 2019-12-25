node{
  stage('SCM Checkout') {
    git 'https://github.com/mackenzies1818/maven_test'
  }
  stage('Compile-Package') {
    sh 'mvn package'
  }

}
