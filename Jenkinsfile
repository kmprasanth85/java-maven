node{
  stage ('SCM checkout'){
    git 'https://github.com/kmprasanth85/java-maven'
  }
  stage ('Compile and package'){
    //If the mavn package is not getting automatically use below line to build the package and comment sh 'mvn package'
      def mvnHOME = tool name: 'maven', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
    //sh 'mvn package'
  }
}
