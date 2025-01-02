## Security Breach: Cyberhaven Chrome Extension Compromise
   A phishing attack compromised a Cyberhaven employee's access to the Google Chrome Web Store, allowing attackers to publish a malicious version of Cyberhaven's Chrome extension. The compromised extension was active for approximately 25 hours before detection and removal.

---
### Overview
- **Date of Incident:** December 24, 2024 – December 25, 2024
- **Affected Organization(s):** Cyberhaven
- **Type of Incident:** Phishing Attack Leading to Supply Chain Compromise

---
### Details
- **Attack Vector:** Phishing email led to unauthorized access to Cyberhaven's Chrome Web Store account.
- **Timeline of Events:**
  - **December 24, 2024:** Phishing attack compromised employee's access; malicious extension version 24.10.4 published.
  - **December 25, 2024, 11:54 PM UTC:** Security team detected the compromise.
  - **December 25, 2024, ~12:54 AM UTC:** Malicious extension removed; clean version 24.10.5 released. 
- **Impact:** Users who auto-updated to version 24.10.4 were exposed to malicious code designed to steal browser cookies and authentication sessions, potentially leading to account takeovers.

---
### Indicators of Compromise (IoCs) 🔥
- **Network IoCs:**
    - cyberhavenext[.]pro14 
    - api.cyberhaven[.]pro14
    - parrottalks[.]info
    - ext[.]linewizeconnect[.]com 
    - readermodeext[.]info 
    - bookmarkfc[.]info 
    - censortracker[.]pro 
    - yujaverity[.]info 
    - wayinai[.]live 
    - vpncity[.]live 
    - cyberhavenext[.]pro 
    - primusext[.]pro 
    - internxtvpn[.]pro
    - uvoice[.]live 
    - policyextension[.]info 
    - castorus[.]info 
    - api[.]searchcopilot[.]co 
    - wakelet[.]ink 
    - tinamind[.]info 
    - iobit[.]pro 
    - graphqlnetwork[.]pro 
    - urban-vpn[.]com
    - yescaptcha[.]pro 
    - 149.28.124[.]8414
    - 149.248.2[.]16014 
    -  148[.]72[.]164[.]10
    - 148[.]72[.]164[.]11 
    - 148[.]72[.]173[.]24 
    - 148[.]72[.]173[.]25 
    - 148[.]72[.]173[.]26 
- **File IoCs:**
    - content.js hash: AC5CC8BCC05AC27A8F189134C2E3300863B317FB14
    - worker.js hash: 0B871BDEE9D8302A48D6D6511228CAF67A08EC6014


---
### Response
- **Detection:** Internal security monitoring identified the unauthorized extension update.
- **Actions Taken:**
  - Revoked compromised credentials.
  - Removed malicious extension version from the Chrome Web Store.
  - Released a clean extension update (version 24.10.5).
  - Notified users and provided guidance on mitigating potential impacts. 
- **Resolution:** Malicious extension was active for approximately 25 hours; clean version deployed promptly after detection.

---
### Recommendations
- **For Users:**
  - Update the Cyberhaven Chrome extension to the latest version immediately.
  - Review account activity for signs of unauthorized access, especially on social media advertising platforms.
  - Change passwords and enable multi-factor authentication on critical accounts.
- **For Organizations:**
  - Educate employees about phishing risks and conduct regular security training.
  - Implement strict access controls and monitor for unusual account activities.
  - Regularly audit and monitor browser extensions for unauthorized changes.

 ---
### References
  - https://www.cyberhaven.com/blog/cyberhavens-chrome-extension-security-incident-and-what-were-doing-about-it
  - https://secureannex.com/blog/cyberhaven-extension-compromise/
  - https://www.securityweek.com/several-chrome-extensions-compromised-in-supply-chain-attack/ 
