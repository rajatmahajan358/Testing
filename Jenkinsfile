pipeline{
    agent any
    stages{
        stage('This is stage One'){
            environment{
                A = 40
            }
            steps{
                script{
                    if (A == 40){
                        echo "Build is even"
                        cd scripts
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