node {
       stage('Clone Repository') {
        checkout scm
    }
      stage('testing cleanup') {
             sh 'pwd'
             sh 'echo $WORKSPACE'
             sh 'ls -lrt'
             sh 'rm -rf $WORKSPACE/*'
             sh 'du -sh $WORKSPACE'
             }
      cleanWs()
}
