node{
  stage('SCM Checkout') {
    git 'https://github.com/mackenzies1818/maven_test'
  }
  stage('Compile-Package') {
    //get maven home path
    def mvnHome = tool name: 'maven_tool', type: 'maven'
    //giving path to mvn command
    sh "${mvnHome}/bin/mvn package"
  }

}
