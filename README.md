# Red Team Ops - Cracking The Perimeter by Joas

## Vulnerability Management

### What Is?

- Vulnerability management programs address today’s modern cybersecurity challenges by instituting a comprehensive and continuous process for identifying, classifying, remediating, and mitigating vulnerabilities before attackers can take advantage of them. At the heart of these vulnerability management programs is often a vulnerability scanner that automatically assesses and understands risk across an entire infrastructure, generating easy-to-understand reports that help businesses properly and rapidly prioritize the vulnerabilities they must remediate or mitigate.

### Steps

- 1. Identifying vulnerabilities 

	- The first and most essential step in any vulnerability management process, of course, is to bring to light all of the vulnerabilities that may exist across your environment. A vulnerability scanner goes about this by scanning the full range of accessible systems that exist—from laptops, desktops, and servers on to databases, firewalls, switches, printers, and beyond.From there, the vulnerability scanner identifies any open ports and services that are running on those systems, logging in to those systems and gathering detailed information where possible before correlating the information it obtains with known vulnerabilities. This insight can be used to create reports, metrics, and dashboards for a variety of audiences.

- 2. Evaluating vulnerabilities

	- Once you’ve identified all the vulnerabilities across your environment, you’ll need to evaluate them in order to appropriately deal with the risks they pose according to your organization’s risk management strategy. Different vulnerability management solutions use different risk ratings and scores for vulnerabilities, but one commonly referenced framework for new programs is the Common Vulnerability Scoring System (CVSS).Vulnerability scores can help organizations determine how to prioritize the vulnerabilities they’ve discovered, it’s important to also consider other factors to form a complete understanding of the true risk posed by any given vulnerability. It’s also worth noting that vulnerability scanners can generate false positives in rare instances, thus underscoring the necessity of including other considerations in addition to risk scores at this stage of the process.

- 3. Treating vulnerabilities 

	- After you’ve prioritized the vulnerabilities that you’ve found, it’s important to promptly treat them in collaboration with your original business or network stakeholders. Depending on the vulnerability in question, treatment usually proceeds according to one of the following three paths: Remediation: Fully fixing or patching a vulnerability so that it cannot be exploited, which is usually the most preferable option whenever possible.Mitigation. When remediation can’t be accomplished, an organization may choose the next best option of reducing the likelihood that a vulnerability will be exploited by implementing compensating controls. This solution should be temporary, buying time for an organization to eventually remediate the vulnerability.Acceptance. If a vulnerability is deemed low-risk or the cost of remediating it is much greater than it would be if it were exploited, an organization may choose simply to take no action to fix the vulnerability.When determining specific treatment strategies, it is best for an organization’s security team, system owners, and system administrators to come together and determine the right remediation approach—whether that’s issuing a software patch or refreshing a fleet of physical servers. Once remediation is considered complete, it’s wise to run another vulnerability scan to make sure that the vulnerability has, in fact, been effectively remediated or mitigated.

- 4. Reporting vulnerabilities 

	- Improving the speed and accuracy with which you detect and treat vulnerabilities is essential to managing the risk that they represent, which is why many organizations continually assess the efficacy of their vulnerability management program. They can take advantage of the visual reporting capabilities found in vulnerability management solutions for this purpose. Armed with the insights needed, IT teams can identify which remediation techniques will help them fix the most vulnerabilities with the least amount of effort. Security teams, for their part, can use this reporting to monitor vulnerability trends over time and communicate their risk reduction progress to leadership. Ideal solutions will include integrations with IT ticketing systems and patching tools to accelerate the process of sharing information between teams. This helps customers make meaningful progress toward reducing their risk. Businesses can also use these assessments to fulfill their compliance and regulatory requirements.

- https://www.rapid7.com/fundamentals/vulnerability-management-program-framework/

## PenTest

### What Is?

- Penetration Testing is a legal, structured procedure to evaluate the security posture of an organization. This practice simulates an attack against the security infrastructure of the enterprise, such as its network, applications, and users, to identify the exploitable vulnerabilities. It determines the efficacy of the company’s security policies, controls, and strategies. To strengthen the system, penetration testers proactively analyse for design flaws, technical weaknesses, and other vulnerabilities. The results of the vulnerability assessment are then comprehensively documented for executive management and the company’s technical audience.Along with that, penetration testing ensures an organization’s adherence to compliance requirements, the ability to respond to security incidents, and its employees’ awareness towards increasing security risks. At the end of the penetration testing process, the findings of identified and exploited flaws are passed on to the organization’s IT and network system managers to make strategic decisions and prioritize remediation efforts.

### Types of PenTest

- Black Box Penetration Testing	

	- A penetration tester has no previous knowledge of the system to be tested. It is like blind testing as the pen testers find their own way into the system.	
	- * Blind Testing – It is a time-consuming and expensive process, where the penetration testing team provided with limited or no information. – This test checks if a threat actor can launch an attack with severely limited information. Mostly, the pen testers receive the name of the organization. It could be costly as it is more time consuming than other forms of penetration testing.
	- * Double-Blind Testing – A few in the firm know about the pen test to be conducted. It evaluates security monitoring, attack identification, and response.– It takes blind testing a step further. Under this form, only one or two employees of the organization are aware of the test. Double-blind testing checks the efficacy of the organization’s security monitoring, incident identification, and response processes.
	- It is time-consuming, requiring a considerable amount of time.	
	- Test to be conducted for evaluating the security stance of the organization. It uses the methodologies of an attacker.	

- Gray Box Penetration Testing

	- A penetration tester has limited knowledge of the system to be used.
	- It needs lesser time than black-box penetration testing.
	- White and Gray box penetrating testing are used to save time and resources.

- White Box Penetration Testing	

	- A penetration tester has complete knowledge of the system to be tested. The known information includes details about IP addresses, network infrastructure schematics, or the protocols in use.	
	- * Announced Testing – Penetration testing conducted after the full co-operation from the IT team.
	- * Unannounced Testing – The organization conducts the test without the knowledge of the IT staff.
	- It reveals vulnerabilities and bugs more quickly.	
	- White and Gray box penetrating testing are used to save time and resources.

### Targeted testing	

- The organization’s IT and penetration testing teams work together to execute targeted testing (sometimes termed as “lights on testing” as the testing process is visible to all the parties involved).

### External testing	

- This form of testing targets only the visible servers or assets of the organizations, such as domain name servers, email servers, web servers, or firewalls. It examines whether an outside attacker can gain access to external devices and their impact.

### Internal testing	

- This testing simulates an internal attack launched by an authorized user with standard access privileges. The result of the test determines how much harm a disgruntled employee can cause.

### https://www.eccouncil.org/what-is-penetration-testing/

## Red Team

### https://github.com/CyberSecurityUP/Awesome-Red-Team-Operations

### A red team consists of security professionals who act as adversaries to overcome cyber security controls. Red teams often consist of independent ethical hackers who evaluate system security in an objective manner. They utilize all the available techniques (discussed below) to find weaknesses in people, processes, and technology to gain unauthorized access to assets. As a result of these simulated attacks, red teams make recommendations and plans on how to strengthen an organization’s security posture.

### https://purplesec.us/red-team-vs-blue-team-cyber-security/

## Adversary Emulation

### Adversary emulation leverages adversary tactics, techniques, and procedures, enhanced by cyber threat intelligence, to create a security test based on real world intrusion campaigns.

### Adversary emulation helps organizations focus their security testing to prioritize threats that their defenders may face each day.

### Successful adversary emulation is a collaborative effort between multiple cybersecurity domains of expertise, particularly red team and cyber threat intelligence (CTI) professionals. CTI professionals work with the security operations center (SOC) and senior leadership to determine what types of threats might target the organization, while red teams work to test and probe defenses. Red teams have the tradecraft and skillset to perform malicious actions to subvert defenses, but that expertise is far more valuable to organizations trying to understand the implications of red team findings on their security posture when it is tied to real world threat data. 

### https://www.scythe.io/library/introduction-to-adversary-emulation

- https://github.com/CyberSecurityUP/Adversary-Emulation-Matrix

## Framework

### Vulnerability Analysis

- Survey the company's risks and vulnerabilities, to start a vulnerability management action plan

### Vulnerability Management

- After the Vulnerability Scanner and the assessment of risks and vulnerabilities, the management process starts to deal with risks and vulnerabilities, applying patches and configuring security control mechanisms.

### Penetration Testing

- After managing and treating risks and vulnerabilities, you can now perform a PenTest, set it according to your need.

### Adversary Emulation

- After performing a PenTest, obtaining a degree of security maturity and addressing the risks and vulnerabilities, we can start with an Adversary Emulation plan, in order to test the efficiency of security controls against TTPs, based on Miter Att&ck. Validate the risk posture and exposure of their business and employees and the performance of enterprise security teams and existing security solutions.

### Cracking The Perimeter

- But what comes after Adversary Emulation?There comes the concept of Cracking The Perimeter, the focus, after testing your business with Adversary Emulation and understanding your company's degree of exposure and where you should focus your security testing to prioritize threats that the defense team faces all the days. Based on TTP models with Miter Att&ck.
- Cracking The Perimeter focuses on testing security defense controls in various ways, we know that 0day is constant and a team prepared to validate whether or not your environment is susceptible to attack from these unknown threats, working together with the team of Threat Intelligence and Threat Hunter to collect threat intelligence, new CVE's, 0days sold to market and vulnerability PoCs. The Perimeter Cracking Team is precisely trained to test security controls and go deep into finding 0days.
- https://www.corelan.be/
- https://www.offensive-security.com/awe-osee/
- https://www.offensive-security.com/exp301-osed/
- https://joasantonio108.medium.com/frameworks-cracking-the-perimeter-246767da6e3f

## Frameworks, Training and Standards - Auxiliary

### http://www.pentest-standard.org/index.php/Main_Page

### https://www.isecom.org/OSSTMM.3.pdf

### https://owasp.org/

### https://www.thec2matrix.com/

### https://attack.mitre.org/

### https://www.nist.gov/cyberframework

### https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html

### https://www.corelan.be/

### https://www.offensive-security.com/

### https://www.iso.org/iso-31000-risk-management.html

### https://www.27001.pt/

### https://pt.pcisecuritystandards.org/index.php

### https://elearnsecurity.com/product/ecxd-certification/

### https://www.sans.org/cyber-security-courses/advanced-exploit-development-penetration-testers/

*XMind - Evaluation Version*
