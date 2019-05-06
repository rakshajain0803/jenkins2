node
{
stage('scm checkout')
{
git "https://github.com/rakshajain0803/jenkins2"
}
stage('compile-package')
{
withMaven(...) {
    bat "mvn clean install"
}
}
}
