node
{
stage('scm checkout')
{
git "https://github.com/rakshajain0803/jenkins2"
}
stage('compile-package')
{
    bat "mvn clean install"
}
stage('output')
{
    java -jar my-app-1.0-SNAPSHOT.jar
}
}
