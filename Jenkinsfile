pipeline {                       // Defines the start of a Declarative Pipeline block; all pipeline code goes inside here
    agent any                   // Specifies that Jenkins can run this pipeline on any available agent/node

    stages {                    // Defines a container for all the pipeline stages (distinct steps or phases)

        stage('scm') {          // Defines a stage named 'scm' (often used for source code management steps)
            steps {             // Contains the actual commands or steps to execute in this stage
                echo "Pulling my code.."      // Prints a message to Jenkins console/log
                echo "pull completed"         // Prints another message after pull
            }
        }

        stage('deploy to server') {    // Defines the 'deploy to server' stage
            steps {                     // Steps to run during deployment
                echo "deploying to server..."
            }
        }

        stage('test') {                 // Defines the 'test' stage
            steps {                     // Test-related commands go here
                echo "testing my code..."
            }
        }
    }
}
