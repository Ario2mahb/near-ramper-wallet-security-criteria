<h1>Wallet Security Criteria:</h1>
A wallet project must have a significant portion of these security program features in place, and shall self-certify that they maintain a security program that is commensurate (sufficiently similar) or better than the elements of the program outlined below. A project may also certify that they have a significant program in place, but intend to enhance the program to a level commensurate with the program outlined below by a given date.

Wallets shall checkbox a statement of compliance to be maintained on the wallet’s GitHub account or Website. The statement may qualitatively discuss the security program and include additional elements, or simply state that it is compliant with the program outlined below. When asserting that open items will be in place within some time period of being listed, target dates shall be included and clearly defined. The overall statement must be dated and the date shall be commensurate with the commit date. All wallet projects must maintain compliance while being included in the wallet listing/selector program. If a wallet is no longer in compliance, or no longer supported, the security statement must reflect that change and the wallet selector team shall be notified. The wallet project shall make verification of the following requirements as easy as possible--maximizing transparency through the use of relevant links pointing toward program descriptions, audit reports, etc. for the user/researcher.

Has a security program in place that covers or is dedicated to the wallet and...

Publishes information about its security program in an easily findable place.

Conducts regular audits of wallet code, at regular intervals of less than a year or based on meaningful code changes.

Conducts regular penetration tests, both “authenticated” and “non-authenticated” upon significant code changes.

Conducts penetration tests on related infrastructure, such as databases, virtual machines, web servers, etc.

Remediates any critical, high, or medium findings from audits (3, 4, an 5 above) in a rapid fashion, as suggested by auditors. Auditors should validate the remediation in their reports.

Makes such reports (audits, penetration tests) publicly available, on at least a summary level.

When making reports (7) available, wallet projects should ensure the equivalent reports appear on the security vendor’s site or simply links to the security vendor’s report. This ensures the authenticity of the audit reports.

Conducts operational readiness reviews and testing or an equivalent process before deployment to production to ensure that code changes have not resulted in unanticipated behavior, compatibility issues, or inclusion of vulnerabilities.

Maintains a testnet wallet, available to developers and security researchers.

Maintains a bug bounty program.

Implements minimal privilege and access policies with regard to supporting infrastructure.

Implements MFA and strong passwords for access to critical related systems, such as domain registration, hosting platforms, cloud platforms, etc.

Conducts known vulnerability and vulnerable dependency checks; and remediates critical, medium, and high findings before deploying to testnet or production.

If the wallet is a browser “extension,” it is listed on the official extension marketplace.

Logs are collected from supporting infrastructure, web servers, etc.

Ensures that logs do not contain sensitive information, are encrypted at rest in storage, and have restricted access with least privilege.

Enables “audit logs” on related platforms (AWS, GCP, monitoring platforms, etc).

Logs shall be maintained for 90 days for forensic purposes.

Security feature shall be enabled in hosting environments, i.e. AWS GuardDuty.

Inputs shall be sanitized.

Code SAST scanning for vulnerabilities and vulnerable dependencies shall be conducted prior to production.

Vulnerability scanning shall be conducted regularly on websites, infrastructure-related VMs, etc. Findings shall be quickly remediated.

Patch management shall be conducted frequently on supporting infrastructure.

VM and bare-metal infrastructure shall be protected by endpoint detection and response software.

An incident monitoring, alerting, and response program shall be in place.

Additional protective technologies, such as web application firewalls, should be put in place and appropriately configured to prevent attacks on the wallet.

White and black lists should be maintained for ip addresses and domains interacting with the wallet to the extent possible.

Reduction in attack surface shall be conducted by removing access to paths and unused ports; properly configuring domains, CSP, etc.

Access to infrastructure should be limited to VPNs or commensurate technology, IP restricted, etc. in order to prevent malicious access. For example, port 22 for the web server would not be accessible from the internet.

OWASP top 10 vulnerabilities shall be regularly tested and remediated.

Tools such as Nessus and Qualys, or similar should be used to scan for vulnerabilities.

Tools such as Burp Suite, or similar should be used to instrument and and analyze the interaction of the wallet with the browser for security issues.

Playbooks for public disclosure and communication to stakeholders and users should be prepared in advance and practiced via tabletop exercises in order to ensure rapid response and disclosure to protect such stakeholders and their assets.

An incident response retainer should be considered.

Wallet projects should clearly inform users of risks, risky behavior, best practices in the use of the wallet, and the most secure methods for using the wallet.

Wallet projects should have a clear path to reporting and receiving help on issues that is easily found by users.

Sensitive information should not be stored in the client-side wallet in a way that could be scraped from storage by malicious software, such as keys, recovery phrases, etc.

Encryption of sensitive data should likewise not rely on hard-coded keys or weak ciphers.

A user’s ability to recover their wallet under various circumstances should be clearly spelled out to the user when setting up the wallet.

Communication between infrastructure elements should be secured to the maximum extent possible. Please link to your the statement on your website or GitHub repo showing a statement of compliance. Please put link below (even if it is a placeholder).