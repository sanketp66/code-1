# code-1
# addition

pipeline {
    agent any
    stages {
        stage('Addition') {
            steps {
                script {
                    def num1 = 5
                    def num2 = 3
                    def result = num1 + num2
                    echo "The result of addition is: ${result}"
                }
            }
        }
    }
}
