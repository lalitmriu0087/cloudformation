pipeline {
    agent any
    stages {
        stage('Submit stack') {
            steps {
           sh "export AWS_DEFAULT_REGION=us-west-2"
           sh "aws cloudformation deploy --template-file pipeline.yml --stack-name lalitstack --region 'us-west-2'"
				
           }
        }
    }
}
