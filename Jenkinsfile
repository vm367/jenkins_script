pipeline{
agent any
stages 
{
stage('Build') 
{
steps{
def yaml = readYaml file: "test.yaml"
echo yaml
}
}
}
}
