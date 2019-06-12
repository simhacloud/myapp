node {
  stage('SCM Checkout'){
  git 'https://github.com/simhacloud/myapp'
  }
  stage ('Compile-Package'){
  sh 'clean-verify'
  }
  }
