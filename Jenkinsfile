pipeline

{
agent any
stages
{
stage('Build')
{
steps
{
bat "mvn clean"
}
}
stage('deploy')
{
steps{
echo 'deploying the code'
}
}
stage('test')
{
steps{
bat "mvn test"
}
}
stage('Release')
{
steps{
echo 'releasing the project'
}
}
}
}