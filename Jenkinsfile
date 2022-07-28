pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
           sh "export AWS_DEFAULT_REGION=us-west-2"
		   sh "aws cloudformation create-stack --stack-name jenkinsstack --template-body file:://vpc2.yml --region 'us-west-2'"
				
           }
        }
    }
}