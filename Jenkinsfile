A = 40
pipeline{
    agent any
    stages{
        stage('This is stage One'){
            environment{
              B=15  
            }
            steps{
                script{
                    if (A == 40){
                        echo "Build is even"
                        sh "pwd"
                        sh "ls"
                        sh "bash ./Hello.sh"
                    }
                    else{
                        echo "Build is odd"
                    }
                }
            }
        }
    }
}