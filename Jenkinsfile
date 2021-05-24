pipeline {

    agent any

    triggers {
        pollSCM('* * * * *')
    }

    stages {

        stage('Testing') {

            parallel {
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

                stage('Analyze source code') {
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

        stage('Analyze') {

            parallel {
                stage('Push artifact') {
                    steps {
                        sh 'echo testing code'
                    }
                }

                stage('Analyze image') {
                    steps {
                        sh 'echo testing code'
                    }
                }

                stage('Security scanning') {
                    steps {
                        sh 'echo testing code'
                    }
                }
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

            parallel {
                stage('E2E Tests') {
                    steps {
                        sh 'echo testing code'
                    }
                }

                stage('Perf tests') {
                    steps {
                        sh 'echo testing code'
                    }
                }

                stage('Security scans') {
                    steps {
                        sh 'echo testing code'
                    }
                }

            }

        }

        stage('Deploy to Prod') {
            steps {
                sh 'echo deploying to dev environment'
            }
        }

        stage('E2E Tests Prod') {
            parallel {
                stage('Smoke tests') {
                    steps {
                        sh 'echo testing code'
                    }
                }

                stage('E2E tests') {
                    steps {
                        sh 'echo testing code'
                    }
                }

                stage('Security tests') {
                    steps {
                        sh 'echo testing code'
                    }
                }

            }
        }

    }

    stage('Canary Tests') {
        parallel {

            stage('Activate feature flags') {
                steps {
                    sh 'echo testing code'
                }
            }

            stage('Release To Some Users') {
                steps {
                    sh 'echo testing code'
                }
            }
        }
    }

    stage('Release to Prod') {
        steps {
            sh 'echo deploying to dev environment'
        }
    }

}