pipeline{
	agent any
	stage{
		stage('One'{
		steps{
			echo 'Hi This is demo'
			}
		stage('Two'){
		steps{
			input('Do you want to proceed')
			}
		}
		stage('Three'){
			when {
				not { 
				branch "master"
				}
			}
			steps { 
				echo "Hello" 
			}
}
