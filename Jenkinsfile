node {
    stage('Gitclone') {
	    git credentialsId: '1c13f517-c8eb-43dd-8cdd-8db5924eb4b3', url: 'https://github.com/kartikeyapro/ks.git'
	     
    }
    stage('Maven version') {
	  powershell 'mvn --version'
      
    }
	stage('Java version') {
	   powershell 'java -version'
      
    }
	stage('Maven Validate') {
	  powershell 'mvn validate'
      
    }
	stage('Maven Compile') {
	   powershell 'mvn compile'
      
    }
	stage('Maven Test') {
	  powershell 'mvn test'
      
    }
	stage('Maven Package') {
	   powershell 'mvn package'
      
    }
	
}

