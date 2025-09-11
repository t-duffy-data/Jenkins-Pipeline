pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo "Tool used: Maven"
                echo "Compiling source code..."
                echo "Packaging application..."
                sleep 1
            }
        }
        stage('Unit and Integration Tests'){
            steps{
                echo "Tool used: JUnit"
                echo "Unit testing..."
                echo "Integration testing..."
            }
        }
        stage('Code Analysis'){
            steps{
                echo "Tool used: OWASP Dependency-Check"
                echo "Analysing code..."
            }
        }
        stage('Security Scan'){
            steps{
                echo "Tool used: SonarQube"
                echo "Scanning for vulnerabilities..."
            }
        }
        stage('Deploy to Staging'){
            steps{
                echo "Tool used: AWS EC2 Instance"
                echo "Deploying to staging server..."
            }
        }
        stage('Integration Tests on Staging'){
            steps{
                echo "Tool used: Selenium"
                echo "Integration testing"
            }
        }
        stage('Deploy to Production'){
            steps{
                echo "Tool used: AWS EC2 Instance"
                echo "Deploying to production..."
            }
        }
    }

}


