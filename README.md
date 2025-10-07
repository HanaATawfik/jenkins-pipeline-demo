# Jenkins Pipeline Demo

## Overview
This repository demonstrates a basic Jenkins pipeline implementation using declarative pipeline syntax. It showcases a simple CI/CD workflow that can be extended for more complex applications.

## Repository Structure
- **Jenkinsfile**: Contains the Jenkins pipeline definition using declarative syntax
- **script.sh**: A shell script that is executed as part of the pipeline

## Pipeline Workflow
The pipeline consists of two stages:

1. **Clone Repository**: 
   - Checks out the code from the repository
   - Ensures the latest version of the code is used for the build

2. **Run Script**:
   - Executes the shell script (`script.sh`)
   - Demonstrates how to incorporate shell scripts into your pipeline

## How to Use This Template

### Prerequisites
- Jenkins server with Pipeline plugin installed
- Git installed on the Jenkins server
- Appropriate permissions for the Jenkins user to execute shell scripts

### Setup Instructions
1. Create a new Jenkins pipeline job
2. Configure it to use this repository as the source
3. Point it to the Jenkinsfile in the repository
4. Run the pipeline

## Extending the Pipeline
This basic pipeline can be extended in several ways:

- Add testing stages (unit tests, integration tests)
- Include build stages for different types of applications
- Implement deployment stages for various environments (dev, staging, production)
- Add quality gates using SonarQube or similar tools
- Configure notifications via email, Slack, or other communication channels

## Best Practices Demonstrated
- Separation of pipeline definition (Jenkinsfile) from application code
- Using descriptive stage names
- Keeping the pipeline code in version control alongside application code

## License
This project is available for educational and professional use.

## Author
Created by Hana A. Tawfik