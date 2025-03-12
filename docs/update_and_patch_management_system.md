## 5\. Set Up a Robust Update and Patch Management System

If you ship a product, you must provide free security updates for its entire lifecycle, for no less than 5 years, unless the product’s expected lifetime is shorter. [Recital 60](https://eur-lex.europa.eu/eli/reg/2024/2847/oj/eng#rct_60) and [Annex I Part II](https://eur-lex.europa.eu/eli/reg/2024/2847/oj/eng#anx_I) highlight this requirement. 

### Use OTA (Over-the-Air) updates
CRA insists on the ability to perform risk mitigation on running devices. You’ll need to enable secure, remote updates that ensure that all devices are patched without manual intervention.  
*Balena provides a full Device Management suite for patching and updates.*

Automate vulnerability tracking
Use tools to detect outdated software and CVEs (Common Vulnerabilities and Exposures).  
*Balena will provide CVEs for our images in the future, so you will just need to monitor your containers' libraries and code*

### Establish a patching procedure
Define the frequency of updates, the deployment process, and how users will be notified. Ensure mechanisms are in place to facilitate users in applying security patches or updates easily.  
*By using balena you will allow for automatic updates, pinning releases and selecting different balenaOS versions.*

### Enable rollback mechanisms
If an update fails, devices should revert to a stable version to prevent outages.  
*balenaOS verifies the integrity of a firmware update, rolling back automatically. Regarding the applications, rollbacks are performed manually or programmatically by selecting the versions you want for a single device or a set of them.*
