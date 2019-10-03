pipeline {
agent any 
	parameters {
	string(name: 'Person',defaultValue:'Select Option',description:'Run your jenkins with parmater')	
	}
stages{
   stage('Initialize'){
     steps{
         echo 'Initialize your project !'
		}
	}
	
	stage('Build'){
	     steps{
		      echo 'Building your project !'
             }
         }
    }


}
