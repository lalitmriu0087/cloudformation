pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
           sh "export AWS_DEFAULT_REGION=us-west-2"
		   sh "aws cloudformation create-stack --stack-name jenkinsstack1 validate-template --template-body file:://vpc2.json --region 'us-west-2'"
				
           }
        }
    }
}
