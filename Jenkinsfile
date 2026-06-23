pipeline{
    agent any

    stages{

        stage('Terrraform Init'){
            steps{
                echo "terraform init"
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
