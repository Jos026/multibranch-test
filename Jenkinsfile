pipeline {
    agent linux

    stages {
        stage("stage1") {
            steps {
                echo "Hello World"
            }
        }
        stage('stage2') {
            steps {
                echo "executing"
                sh "python hello-world.py"
            }
        }
        stage('stage3') {
            steps {
                echo "Success"
            }
        }
        
    }
}
