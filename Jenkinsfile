//A = "${env.BUILD_NUMBER}"
A = 4
pipeline{
    agent any
    stages{
        stage('This is stage One'){
            environment{
                A = 2
            }
            steps{
                script{
                    if (A == 4){
                        echo "Build is even"
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