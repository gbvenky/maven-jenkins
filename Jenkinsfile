#!groovy

node {
	   
	stage('Checkout'){

          checkout scm
       }

       stage('Compiling'){

          sh 'mvn install'
       }
	   
      stage('Sonar') {
                    //add stage sonar
                    sh 'mvn sonar:sonar'
                }
       
}
