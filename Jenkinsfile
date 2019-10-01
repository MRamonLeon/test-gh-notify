node ('docker-dedicated') {
    stage("notify github") {
        checkout scm

        githubNotify context: 'testing',
            description: 'A message description',
            status: 'SUCCESS'
    }
}
