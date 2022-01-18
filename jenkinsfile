node {
    stage('clone') {
    git 'https://github.com/oukettouk/jenkins-helloworld-1.git'
}
    stage('Build') {
    sh 'javac Main.java'
}
stage('Run') {
    sh label: 'compile & execute', script: 'java Main'
}
}
