pipeline {
agent any
tools{
maven 'mvn 3.9.4'
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
