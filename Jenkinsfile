pipeline {

		agent {
		
				label 'built-in'
		}
		
		stages {
		
		
			stage ('stage-1'){
			
			steps {
			
			echo "getting started"
			
			}
			
			}
		
		
		
			stage ('parallel-stages-2'){
			
			parallel {
			
			stage ('sleep-1'){
			
				steps {
				
						sleep 2
				
				}
		
			
			}
			
			stage ('sleep-2'){
			
				steps {
				
						sleep 2
				
				}
		
			
			}
			
			}


}


			stage ('stage-3'){
			
			steps {
			
			echo "thankyou"
			
			}
			
			}
}
}

