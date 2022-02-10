node{
stage('SCM Checkout'){
  
git 'https://github.com/Anusha158/Jenkins-git'
}
stage('Compile-Package'){
  def mvHome=tool name: 'MAVEN_HOME', type: 'maven'
  sh "${mvHome}/bin/mvn package"
}
}
