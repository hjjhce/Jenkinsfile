Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'php' }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
                sh '''
                	echo 'Multiline shell steps works too'
                	ls -alh
                	echo 'only test'
                '''
            }
        }
    }
}
