pipeline{
    agent any
    stages{
        stage('This is stage One'){
            environment{
                A = 2
            }
            steps{
                script{
                    if (${env.BUILD_NUMBER} % 2 == 0){
                        echo "Build is even"
                    }
                    else{
                        echo "Build is odd"
                    }
                }
            }
        }
    }
}