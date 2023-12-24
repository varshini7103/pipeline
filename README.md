pipeline{
agent any
stages(
stage('build'){
steps{
echo 'building a file'
}
}
stage('test'){
steps{
echo 'testing a file'
}
}
stage('deploy'){
steps{
echo 'deploying a file'
