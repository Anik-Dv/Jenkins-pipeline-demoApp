pipeline{

    agent any

    stages{

        stage("Compile File"){
            steps{
                javac demo.java
                echo "compilation complete"
            }
        }

        stage("Test Files"){
            steps{
                echo "Testing File Completed"
            }
        }

        stage("Build File"){
            steps{
                java demo
                echo "Build File"
            }
        }
    }

}