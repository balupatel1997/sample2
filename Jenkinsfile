pipeline
{
agent any
stages{
stage("Build Applications"){
steps{
bat 'mvn clean install'
}
}
stage("Deploy application to Mulesoft Cloudhub"){
steps{
bat 'mvn package deploy -DmuleDeploy'
}
}
}
}