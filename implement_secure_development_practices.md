## 4\. Implement Secure Software Development Practices

### Use secure coding practices
Avoid common vulnerabilities like buffer overflows or insecure APIs and implement policies like input validation, authentication management, access control, and data at rest and in transit protection. For a comprehensive checklist of secure coding practices, you can refer to the [OWASP Secure Coding Practices Checklist](https://owasp.org/www-project-secure-coding-practices-quick-reference-guide/stable-en/02-checklist/05-checklist.html).

### Implement SBOM** (Software Bill of Materials)
Keep track of all software components and dependencies to manage vulnerabilities. ([Annex I, Part II.1](https://eur-lex.europa.eu/eli/reg/2024/2847/oj/eng#anx_I))  
*Balena will provide you with an SBOM for everything contained in the OS build (Currently you obtain it manually, but in the future, it will be part of the OS meta-data and API calls).*

### Secure boot & encryption** – 
The CRA requires that the authenticity and integrity of software are guaranteed, which technically can be solved by using Secure Boot and Full Disk Encryption. [Annex I](https://eur-lex.europa.eu/eli/reg/2024/2847/oj/eng#anx_I) has several points related to this.  
*Balena provides Secure Boot and Full Disk Encryption for selected device types.*

### Hardened OS
Use minimal, protected, containerized OS setups to reduce the attack surface, and test for vulnerabilities before every release.  
*BalenaOS provides a secure configuration on freshly installed builds.*
