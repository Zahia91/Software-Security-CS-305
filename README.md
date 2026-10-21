# CS 305 Portfolio Reflection: Artemis Financial

## Project Artifact

**Selected Artifact:** Artemis Financial Practices for Secure Software Report

This report demonstrates my ability to improve software security, apply secure coding practices, test an application, and evaluate software vulnerabilities.

## 1. Client and Software Requirements

Artemis Financial was my client for this project. The company needed to improve the security of its software and protect information exchanged between the application and its users. My task was to implement secure communication using HTTPS and add a checksum feature to help verify data integrity. I also reviewed the application's dependencies to identify potential security vulnerabilities.

## 2. Identifying Vulnerabilities and the Importance of Secure Coding

I did well at examining the application's security requirements, reviewing dependency vulnerabilities, and applying security improvements. I used the Dependency-Check tool to identify potentially vulnerable software components and reviewed the findings before deciding what needed attention. Secure coding is important because vulnerabilities can expose sensitive information, allow unauthorized access, and damage a company's reputation. Software security helps protect customers, reduce business risks, build trust, and support the company's long-term success.

## 3. Most Challenging or Helpful Part of the Assessment

One of the most challenging parts was configuring HTTPS and the keystore so that the Spring Boot application could run securely. Reviewing Dependency-Check results was also helpful because it showed me how third-party libraries can introduce security risks. I learned that scan results need to be reviewed carefully instead of assuming every finding is a confirmed vulnerability or immediately suppressing it.

## 4. Increasing Layers of Security

I increased security by configuring HTTPS, using a keystore for the server's certificate, implementing a SHA-256 checksum endpoint, and scanning the project's dependencies for known vulnerabilities. These measures address different concerns: encrypted communication, certificate-based server identity, data-integrity checking, and dependency risk. In future projects, I would use tools such as OWASP Dependency-Check, review applicable CVE and CWE information, evaluate vulnerability severity and exploitability, and prioritize mitigations based on risk. I would also follow current security guidance and verify that any proposed suppression is a legitimate false positive.

## 5. Testing Functionality and Security

I checked that the Spring Boot application started successfully and that the checksum page returned the expected type of result. I also verified that the application used HTTPS on the configured local port and generated a SHA-256 checksum for the displayed data. After making code and configuration changes, I ran the application again and reviewed the Dependency-Check report to look for potential vulnerabilities in its dependencies. These checks helped me evaluate functionality and identify security concerns, although a successful test or scan does not guarantee that an application is completely secure.

## 6. Useful Resources, Tools, and Practices

The tools and resources I used included Java, Spring Boot, Maven, Eclipse, HTTPS/TLS configuration, a PKCS#12 keystore, SHA-256 hashing, and OWASP Dependency-Check. I also learned the importance of reviewing vulnerability reports, understanding CVE information, validating code changes, and retesting an application after refactoring. These practices will be useful in future programming assignments and cybersecurity tasks because they help identify risks throughout the development process.

## 7. Demonstrating My Skills to Future Employers

I could show future employers my completed Artemis Financial Practices for Secure Software Report, relevant code examples, the checksum functionality, and screenshots demonstrating that the application ran using HTTPS. I could also show a Dependency-Check report to demonstrate my experience reviewing software vulnerabilities and evaluating security findings. This project provides examples of my skills in Java application development, secure configuration, vulnerability assessment, testing, and technical documentation. Before sharing any project publicly, I would remove private keys, keystore files, passwords, and other sensitive information.
