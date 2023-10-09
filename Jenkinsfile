Pipeline {

    agent any

    Stages {

        Stage("Compile File") {
            Steps {
                echo "compilation complete"
                javac demo.java
            }
        }

        Stage("Test Files") {
            Steps {
                echo "Testing File Completed"
            }
        }

        Stage("Build File") {
            Steps {
                echo "Build File"
                java demo
            }
        }
    }

}