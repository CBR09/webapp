node('swarm') {
   stage 'Stage 1: Clone source from git'
   git branch: 'develop', url: 'https://github.com/CBR09/webapp'
   stage 'Stage 2: Build docker image'
   sh 'docker build -t cbr09/webapp .'
   stage 'Stage 3: Check docker list'
   sh 'docker images'
}
