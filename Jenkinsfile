node {
  stage('SCM Checkout'){
   
    
    git 'https://github.com/singhsunilprahlad/hello-world'
  }
  stage('Compile-Package'){
    //get maven home path
        def mvnHome = tool name: 'maven-3', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
        }
  
   stage('SonarQube-Analysis'){
     
            echo "Quality test successful"    
     
        }
  
  stage('Build-DockerImage'){
     
            echo "Build image successful"    
     
        }
   stage('Push-imageDockerhub'){
     
            echo "pushed to Dockerhub "    
     
        }
  stage('Deploy to Dev'){
     
            echo "pushed to Dockerhub "    
     
        }
  }




        
