//A = "${env.BUILD_NUMBER}"
pipeline{
    agent any
    stages{
        stage('This is stage One'){
            environment{
                A = 4
            }
            steps{
                script{
                    if (A == 4){
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