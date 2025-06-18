Provisioned an EC2 instance (t2. large) and installed Jenkins, Docker, Git, Node.js, Trivy, and OWASP Dependency Check.
Automated the CI/CD lifecycle for a Node.js application using a custom Jenkins pipeline
Integrated SonarQube via Docker for static code analysis and set up quality gates with credential management in Jenkins.
Added security scans using Trivy (filesystem & image) and OWASP tools for vulnerability detection.
Built Docker images, pushed them to DockerHub, and deployed containers on EC2 using shell scripts.
Optimized pipeline with steps for: workspace cleanup → code checkout → quality scan → vulnerability scan → Docker build & push → image scan → container deployment.
Tech Stack Used: Jenkins, Docker, Git, SonarQube, Node.js, Trivy, OWASP Dependency Check, AWS EC2, Shell Scripting
