pipeline {
agent any
tools{
maven 'my_maven'
}
stages {
stage('Commit') {
steps {
echo 'This is the start of the pipeline'
bat 'mvn clean'
bat 'mvn compile'
bat 'mvn test'
}
}
}
}
