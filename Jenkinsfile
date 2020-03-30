A = "${env.BUILD_NUMBER}"
pipeline{
    agent any
    stages{
        stage('This is stage One'){
            environment{
                A = 2
            }
            steps{
                script{
                    if (A == 0){
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