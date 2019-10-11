pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'php --version'
                sh '''
                	echo 'Multiline shell steps works too'
                	ls -alh
                	echo 'test again'
                '''
            }
        }
    }
}
