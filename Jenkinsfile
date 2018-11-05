pipeline{
    agent any
    stages{
        stage('Build master'){
            when{
                branch 'master'
            }
            steps{
                echo "Building master branch successfully"
            }
        }
        stage('Build Dev'){
            when{
                branch 'dev'
            }
            steps{
               echo 'Building dev branch successfully' 
            }
        }  
    }
}
