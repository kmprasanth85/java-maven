node{
  stage ('SCM checkout'){
    git 'https://github.com/kmprasanth85/java-maven'
  }
  stage ('Compile and package'){
    sh 'mvn package'
  }
}
