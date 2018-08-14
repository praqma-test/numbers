node("master") {
    stage("checkout") {
        checkout scm
    }
    stage("stuff") {
        sh 'git status'
        sh 'git branch'
        sh 'git show HEAD'
        sh 'git log --oneline -n10'
    }
}

