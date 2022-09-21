node {
    stage('Gitclone') {
	    git credentialsId: '1c13f517-c8eb-43dd-8cdd-8db5924eb4b3', url: 'https://github.com/kartikeyapro/ks.git'
	     
    }
    stage('Maven version') {
	  sh 'mvn --version'
      
    }
	stage('Java version') {
	   sh 'java -version'
      
    }
	stage('Maven Validate') {
	  sh 'mvn validate'
      
    }
	stage('Maven Compile') {
	   sh 'mvn compile'
      
    }
	stage('Maven Test') {
	  sh 'mvn test'
      
    }
	stage('Maven Package') {
	   sh 'mvn package'
      
    }
	stage('Maven Deploy') {
	   sh 'mvn deploy'
    }
	
}
