pipeline {
    agent any

    stages {
        stage('initialize') {
            steps {
                'sh terraform init'
            }
        }
        stage('format the code') {
            steps {
                sh 'terraform format'
            }
        }
         stage('validate') {
            steps {
                 sh 'terraform validate'
            }
        }
       stage('validate') {
            steps {
                 sh 'terraform validate'
            }
        }
      stage('plan') {
            steps {
                 sh 'terraform plan'
            }
        }  
        stage('apply') {
            steps {
                 sh 'terraform apply'
            }
        }
    }
}
