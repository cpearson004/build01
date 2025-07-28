pipeline {
agent any
tools{
maven 'my_maven'
}
stages {
stage('Commit') {
steps {
echo 'This is the start of the pipeline'
mvn clean
mvn compile
mvn test
}
}
}
}
