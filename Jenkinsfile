pipeline{


agent any

stages {

stage('Checkout Source'){ 
steps{
 git 'https://github.com/HarshaSoftSolutions/abc.git'
 }
 }
 
 stage('Deploy App'){
 
 steps{
 script{
 kubernetesDeploy(configs:"sample.yaml",kubeconfigId: "kubeconfig")
 }
 }
 
 }
 
 }
 
 
 }
 
