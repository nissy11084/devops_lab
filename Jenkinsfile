pipeline{
agent any
stages
{
stage('clone ')
{
steps{
git 'https://github.com/nissy11084/devops_lab.git'
}
}
stage('build')
{
steps{
sh 'javac hello.java'
}
}
stage('run')
{
steps
{
sh 'java hello'
}
}
}
}
