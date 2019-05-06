node
{
    stage('scm checkout')
    {
        git "https://github.com/rakshajain0803/jenkins2"
    }
    stage('compile')
    {
        bat "mvn clean compile"
    }
    stage('test')
    {
        bat "mvn test"
    }
    stage('install')
    {
        bat "mvn install -DskipTests"
    }
    stage('execute')
    {
        bat "java -jar ./target/my-app-1.0-SNAPSHOT.jar"
    }
}
