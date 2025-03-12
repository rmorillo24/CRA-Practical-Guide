## 3\. Conduct a Cyber Security Risk Assessment

The CRA mandates that manufacturers assess and address security risks related to their products. [Annex I](https://eur-lex.europa.eu/eli/reg/2024/2847/oj/eng#anx_I) outlines the essential risk assessment and resulting mitigation requirements that both hardware and software manufacturers must follow. 

**You need to perform a risk assessment for every product you make available on the market, monitor how risks change throughout its lifetime, and reassess whenever you add substantial updates. Otherwise, you will not comply.**

The following list provides key steps to ensure compliance with these obligations:

### Identify critical assets
What components of your product are at the highest risk of cyberattacks? (Firmware, OS, third-party libraries, APIs, Interfaces, Storage, etc.)

### Analyze threats
What are the biggest security risks? (Unauthorized access, supply chain vulnerabilities, outdated software, destruction, compromised connected devices, etc.)

### Assess impact
If a vulnerability is exploited, what’s the worst-case scenario? (Data leaks, device takeovers, regulatory penalties, etc.)

### Prioritize mitigations
Implement security features like Secure Boot, Disk Encryption, OTA updates, access controls, and encrypted communications.

### Document the process
Risk assessments must be documented, as they are a mandatory part of the technical documentation for compliance and future audits.

*Balena is developing a framework to automatically identify critical assets and their risks depending on the Device Types and balenaOS versions used in your project.* 
