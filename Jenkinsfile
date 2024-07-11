node {
 stage('clone') {
    git branch: 'main', url: 'https://github.com/mimouneayoub/hello-word.git'
 }
 stage('build') {
    sh 'javac HelloWorld.java'
 }
  stage('run') {
    sh 'java HelloWorld'
 }
 
}
