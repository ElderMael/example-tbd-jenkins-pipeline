pipeline {

    agent any

    triggers {
        cron('* * * * *')
    }

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

        stage('E2E Tests Dev') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('Deploy to Qa') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('E2E Tests Qa') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('Deploy to Staging') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('E2E Tests Staging') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('Deploy to Prod') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('E2E Tests Prod') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

    }

}