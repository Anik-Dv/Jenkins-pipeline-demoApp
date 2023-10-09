pipeline{

    agent any

    stages{

        stage("Compile File"){
            steps{
                echo "compilation complete"
                javac demo.java
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
                java demo
            }
        }
    }

}