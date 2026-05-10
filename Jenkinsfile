pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Stage: Build"
                echo "Task: Building the code using Maven to compile and package the application."
                echo "Tool: Maven"
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo "Stage: Unit and Integration Tests"
                echo "Task: Running unit tests to verify individual components function correctly."
                echo "Task: Running integration tests to verify components work together as expected."
                echo "Tools: JUnit for unit tests, Selenium for integration tests"
            }
        }

        stage('Code Analysis') {
            steps {
                echo "Stage: Code Analysis"
                echo "Task: Analysing source code to ensure it meets industry standards and best practices."
                echo "Tool: SonarQube"
            }
        }

        stage('Security Scan') {
            steps {
                echo "Stage: Security Scan"
                echo "Task: Performing a security scan to identify known vulnerabilities in the code."
                echo "Tool: OWASP Dependency-Check"
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo "Stage: Deploy to Staging"
                echo "Task: Deploying the application to the staging server."
                echo "Tool: AWS CLI deploying to AWS EC2 instance"
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo "Stage: Integration Tests on Staging"
                echo "Task: Running integration tests on the staging environment to verify production-like behaviour."
                echo "Tool: Postman / Newman"
            }
        }

        stage('Deploy to Production') {
            steps {
                echo "Stage: Deploy to Production"
                echo "Task: Deploying the application to the production server."
                echo "Tool: AWS CLI deploying to AWS EC2 instance"
            }
        }

    }
}
