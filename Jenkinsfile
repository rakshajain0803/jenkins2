node
{
stage('scm checkout')
{
git "https://github.com/rakshajain0803/jenkins2"
}
stages('compile-package')
{
def mvnHome= tool name:'maven_3_6_0'. type: 'maven'
sh 'mvn clean install'
}
}
