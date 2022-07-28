pipeline {
    agent any
    stages {
        stage('Submit stack') {
            steps {
           sh "export AWS_DEFAULT_REGION=us-west-2"
           sh "aws cloudformation create-stack --stack-name lalitstack --template-body file:://vpc2.json --region 'us-west-2'"
				
           }
        }
    }
}
