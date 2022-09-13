pipeline{
    agent any
    stages{
        stage('Build master'){
            when{
                    branch 'master'
                }
            steps{
              echo "Master build done"   
            }
        }
        stage('Build dev'){
            when{
                branch 'dev'
            }
            steps{
                echo "Dev build done"
            }
        }
    }
}
