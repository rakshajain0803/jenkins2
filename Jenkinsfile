node
{
stage('scm checkout')
{
git "https://github.com/rakshajain0803/jenkins2"
}
stage('compile-package')
{
def mvnHome= tool name:'maven_3_6_1', type: 'maven'
mvn clean install
}
}
