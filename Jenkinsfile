pipeline{

    agent any

    stages{

        stage("Compile File"){
            steps{
                echo "compilation complete"
                sh 'javac demo.java'
            }
        }

        stage("Test Files"){
            steps{
                echo "Testing File Completed"
            }
        }

        stage("Build File"){
            steps{
                echo "Build File"
                sh 'java demo'
            }
        }
    }

}