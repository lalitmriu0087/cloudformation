pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
           sh "aws s3 ls"
           sh "export AWS_DEFAULT_REGION=us-west-2"
           sh "aws cloudformation create-stack --stack-name lalitstack --template-body file:://vpc2.json --region 'us-west-2'"
				
           }
        }
    }
}
