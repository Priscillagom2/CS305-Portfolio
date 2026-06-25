# CS305-Portfolio
CS 305 Software Security Portfolio
# CS 305 Module Eight Journal – README Reflection

## CS 305 Portfolio Reflection

### Project Artifact

**Artemis Financial Practices for Secure Software Report**

### Reflection

Artemis Financial is a financial services company that wanted to improve the security of its web application while maintaining reliable communication with its clients. The company needed its software updated to support secure HTTPS communication, implement data integrity verification using SHA-256 hashing, and identify and address software security vulnerabilities. The goal was to protect sensitive customer information and ensure the application followed secure software development practices.

One of the things I did well during this project was identifying security weaknesses and implementing solutions that improved the overall security of the application. I configured HTTPS using a self-signed SSL certificate, implemented SHA-256 checksum verification, and verified that the application functioned correctly after making these changes. Coding securely is important because it helps protect sensitive information, prevents security breaches, and builds trust between a company and its customers. Strong software security also reduces financial and reputational risks for an organization.

The most challenging part of the vulnerability assessment was configuring the SSL certificate and troubleshooting the HTTPS configuration. Although it required several attempts, working through the process helped me better understand how certificates, encryption, and secure communications work together in a web application.

I increased the application's security by enabling HTTPS, generating and configuring a self-signed SSL certificate, using SHA-256 hashing for data verification, and reviewing dependency vulnerabilities using OWASP Dependency-Check. In future projects, I would continue using vulnerability scanning tools such as OWASP Dependency-Check and static code analysis to identify potential risks and determine appropriate mitigation strategies before deployment.

To ensure the application remained functional and secure, I tested the application after each major change, verified that it launched successfully in Eclipse, confirmed that the HTTPS endpoint was accessible through the browser, and verified that the checksum was generated correctly. I also reviewed dependency reports and ensured that no new vulnerabilities were introduced after refactoring the code.

Throughout this project, I used several valuable resources and tools, including Eclipse IDE, Maven, Spring Boot, Java Keytool, OWASP Dependency-Check, and GitHub. I also followed secure coding practices such as encrypting communications, validating application functionality after changes, and testing incrementally throughout development. These tools and practices will continue to be useful in future software development projects.

If I were demonstrating my skills to future employers, I would include my completed Artemis Financial Practices for Secure Software Report along with the secure Spring Boot application that demonstrates HTTPS configuration, SSL certificate implementation, SHA-256 checksum generation, and secure coding practices. These artifacts demonstrate my understanding of software security, vulnerability mitigation, secure application development, and testing.
AI Usage Acknowledgment

I used ChatGPT (OpenAI) to assist with proofreading, improving the clarity of my written responses, and explaining technical concepts while completing this assignment. All work was reviewed, edited, and verified by me before submission.
