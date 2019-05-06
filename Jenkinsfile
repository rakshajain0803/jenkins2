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
    bat "cd C:\\Program Files (x86)\\Jenkins\\workspace\\jenkins2MavenPipeline\\target"
    bat "java -jar my-app-1.0-SNAPSHOT.jar"
}
}
