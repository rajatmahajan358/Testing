A = 40
pipeline{
    agent any
    stages{
        stage('This is stage One'){
            environment{
                
            }
            steps{
                script{
                    if (A == 40){
                        echo "Build is even"
                        
                        //sh "bash ./Hello.sh"
                    }
                    else{
                        echo "Build is odd"
                    }
                }
            }
        }
    }
}