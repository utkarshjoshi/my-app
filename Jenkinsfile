
node {
   // This is to demo github action	

   
   stage('SCM Checkout'){
    // Clone repo
	git 'https://github.com/javahometech/myweb'
   }
   
   stage('Compile-Package'){
	def mvnHome = tool name: 'M2_HOME', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
   }
}
