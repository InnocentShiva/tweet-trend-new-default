pipeline {
    agent {
        node {
            label 'maven'    
        }
    }

    stages {
        stage('Clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/InnocentShiva/tweet-trend-new-default.git'
            }
        }
    }
}
