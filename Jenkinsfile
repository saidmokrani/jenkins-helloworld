node {
stage('clone') {
    git 'https://github.com/saidmokrani/jenkins-helloworld.git'
}
stage('build') {
   sh 'javac Main.java'
}
stage('Run') {
  sh 'java Main'
}
}
