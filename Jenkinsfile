node{ 
  stage('SCM Checkout')
  {
        git 'https://github.com/Naitik1998/JDBC' 
  } 
  stage('Compile Package')
  { 
    def mvnHome= tool name: 'Maven 1', type: 'maven' 
    sh "${mvnHome}/bin/mvn package" 
  } 
}
