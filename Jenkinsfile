pipeline{
    agent none
    options{
                timestamps()
            }
    stages{
        stage('Build'){
		agent any
		options{
		skipDefaultCheckout()
		}
            
            steps{
                echo 'Hello World'
            }
        }
    }
}
