pipeline {
    agent any
    environment {
        CI = 'true'
    }
    stages {
        stage('Initilization') {
            steps {
                sh "echo ${BRANCH_NAME}"
                sh "echo ${BUILD_ID}"
                sh "echo ${BUILD_NUMBER}"
                sh "echo ${TAG_NAME}"
            }
        }
        // stage('Build') {
        //     steps {
        //         sh 'npm install'
        //     }
        // }
        // stage('Test') {
        //     steps {
        //         sh './jenkins/scripts/test.sh'
        //     }
        // }

        // stage('Deliver for development') {
        //     when {
        //         branch 'development'
        //     }
        //     steps {
        //         sh 'echo $(pwd)'
        //         sh 'chmod +x ./jenkins/scripts/deliver-for-QA.sh'
        //         input message: 'Finished using the web site? (Click "Proceed" to continue)'
        //         sh 'sh ./jenkins/scripts/deliver-for-QA.sh'
        //         sh './jenkins/scripts/kill.sh'
        //     }
        // }

        // stage('Deliver for QA') {
        //     when {
        //         branch 'QA'
        //     }
        //     steps {
        //         sh 'echo $(pwd)'
        //         sh 'chmod +x ./jenkins/scripts/deliver-for-QA.sh'
        //         input message: 'Finished using the web site? (Click "Proceed" to continue)'
        //         sh 'sh ./jenkins/scripts/deliver-for-QA.sh'
        //         sh './jenkins/scripts/kill.sh'
        //     }
        // }
        // stage('Deploy for production') {
        //     when {
        //         branch 'production'
        //     }
        //     steps {
        //         sh './jenkins/scripts/deploy-for-production.sh'
        //         input message: 'Finished using the web site? (Click "Proceed" to continue)'
        //         sh './jenkins/scripts/kill.sh'
        //     }
        // }
    }
}
