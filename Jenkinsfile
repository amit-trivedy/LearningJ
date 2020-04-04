node{
  stage('SCM Checkout'){
    git 'https://github.com/amit-trivedy/LearningJ'
    }
    
  stage('Compile-Package'){
    def MavenHome = tool name: 'maven-3', type: 'maven'
    sh "{$MavenHome}/opt/apache-maven-3.6.3"
   }
   }
    
