pipeline {
agent any
stages {
stage('devops class') {
steps {
build(job:'devops class',propagate: false)
}
}
stage('tester') {
steps {
echo "success"
}
}
stage('release') {
steps {
echo "success"
}
}
}
}
