pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://ec2_parameter_example.json --region 'ap-south-1'"
              }
             }
            }
            }
