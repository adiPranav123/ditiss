pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/your-username/system-info-script.git'
            }
        }

        stage('Run Script') {
            steps {
                script {
                    sh './get_system_info.sh'
                }
            }
        }
    }
}

 
