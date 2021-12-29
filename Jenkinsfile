pipeline {

    agent any

    stages{

        stage("build"){
            steps{
                echo 'building...'
                nodejs('Node14'){
                    sh 'yarn install'
                    sh 'yarn build'
                }
                echo 'build done'
            }
        }
    }
}