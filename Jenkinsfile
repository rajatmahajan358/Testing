pipeline{
    agent any
    stages{
        stage('This is stage One'){
            environment{
                A = 2
            }
            steps{
                script{
                    if (A==2){
                        echo "A is even"
                    }
                    else{
                        echo "A is odd"
                    }
                }
            }
        }
    }
}