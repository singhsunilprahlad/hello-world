node {
  stage('SCM Checkout'){
   
    
    git 'https://github.com/singhsunilprahlad/hello-world'
  }
  stage('Compile-Package'){
    //get maven home path
        def mvnHome = tool name: 'maven-3', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
        }
        }
        
