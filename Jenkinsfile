pipeline {
    agent any

    stages {
        stage('one') {
            steps {
                echo 'This is my first stage'
            }
        }
        stage('two') {
            steps {
                echo 'This is my two stage'
                echo "hey guys"
            }
        }
        stage('three') {
            steps {
                echo 'This is my three stage'
                build "parallel-pipeline"
            }
        }
    }
}

