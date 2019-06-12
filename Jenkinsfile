node {
  stage('SCM Checkout'){
  git 'https://github.com/simhacloud/myapp'
  }
   stage('Mvn Package'){
	   // Build using maven
	   
	   sh "${mvn} clean package deploy"
}
  }
