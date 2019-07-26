node{
stage('scm'{
 def mvnHome= tool name: '', type: 'maven'
  
git 'https://github.com/PoojaJoshi1102/Demo'
}
stage('compile-package'){
   def mvnHome= tool name: '', type: 'maven'
  sh "${mvnHome}/bin/mvn package
}
}
