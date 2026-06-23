pipeline{
    agent any

    stages{

        stage('Terrraform Init'){
            steps{
                sh 'terraform init'
            }
        }

        stage('Terraform Plan'){
            steps{
                sh 'terraform plan'
            }
        }

        stage('Terraform Apply'){
            steps{
                sh 'terraform apply -auto-approve'
            }
        }

    }
}