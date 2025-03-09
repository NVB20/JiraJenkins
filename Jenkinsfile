pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                jiraComment body: 'test comment from Jenkins', issueKey: 'CPG-8'
            }
        }
    }
}
