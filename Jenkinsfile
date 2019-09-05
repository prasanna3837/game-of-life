node('ubuntu_A') {
    stage('git'){
        git branch:'master', url:'https://github.com/prasanna3837/game-of-life.git'
    }
    stage('build') {
    sh label: '', script: 'mvn package'
    }
}
