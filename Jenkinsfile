pipeline {

    agent any

    stages {

        stage('Testing') {

            paralell {
                stage('Unit tests') {
                    steps {
                        sh 'echo testing code'
                    }
                }

                stage('Integration tests') {
                    steps {
                        sh 'echo testing code'
                    }
                }

                stage('Isolation tests') {
                    steps {
                        sh 'echo testing code'
                    }
                }
            }
            
        }

        stage('Build') {
            steps {
                sh 'echo building artifacts'
            }
        }

        stage('Deploy to Dev') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('Smoke Tests') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('Deploy to Qa') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('Smoke Tests') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('Deploy to Staging') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('Smoke Tests') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('Deploy to Production') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('Smoke Tests') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

    }

}