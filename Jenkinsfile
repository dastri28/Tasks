pipeline {
    agent any
    stages {
        stage('Git') {
            steps {
               git 'https://github.com/dastri28/Tasks.git'
            }
        }
        stage('Execute Two Script') {
            steps {
                sh 'bash bashfile.sh'
                sh 'python3 pythonfile.py'
                
            }
        }
    }
}
