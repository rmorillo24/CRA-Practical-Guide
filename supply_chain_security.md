## 6\. Strengthen Supply Chain Security

CRA places accountability on companies to ensure their entire supply chain is secure—not just their own software, but every component, library, and vendor they use.

### Work only with CRA-compliant manufacturers
Ensure vendors provide SBOMs, vulnerability disclosures, a clear End of Life policy, and security support commitments. If you are acquiring hardware from European companies they should be CRA compliant. If they are non-Europeans, their distributor or importer should guarantee that the manufacturer complies.  
*Balena is currently working on the CRA requirements and will provide users with the relevant information required to validate our compliance.*

### Monitor dependencies
Open-source and third-party libraries must be regularly checked for vulnerabilities (e.g., through CVE monitoring). You need to monitor for deployed versions and provide preventive security updates for existing products in the field.  
*Balena will monitor balenaCloud and balenaOS variants, making reports available, so you will only be responsible for your application dependencies.*

### Use trusted cryptographic standards
Ensure that all firmware, software updates, and components from supply chain partners are digitally signed and encrypted using industry-approved standards (e.g., TLS, AES, RSA). This prevents tampering, unauthorized modifications, and supply chain attacks such as firmware backdoors or rogue software updates.
