# Cybersecurity Fundamentals - Labs & Projects 
 <html>
	<body> 
		<h1> Performing Reconnaissance and Probing Using Common Tools </h1>
			<h2> Overview </h2>
				<p>I engaged with various essential applications and tools vital for cybersecurity exploration.
				These included RSA Network Investigator, Wireshark, Nessus, FileZilla, Zenmap, and PuTTY. Through hands-on exercises,
				I delved into fundamental concepts such as promiscuous mode in Wireshark, which facilitates comprehensive packet
				analysis across subnets or VLANs. I also explored the distinctions between Wireshark and NetWitness Investigator, 
				discovering their unique approaches to network investigation—Wireshark provides a granular view of individual 
				packets, while NetWitness Investigator categorizes and organizes traffic for pattern analysis. Moreover, 
				I learned the importance of selecting the appropriate interface in Wireshark to filter data accurately, 
				enabling focused analysis within the student lab environment. 
				Command-line proficiency was honed as I executed an Intense Scan with Zenmap,
				employing syntax precision to probe a target subnet effectively. Throughout the lab, 
				I engaged with various scan options offered by Zenmap, such as Ping Scan, Intense Scan, and Quick Scan, 
				each serving distinct purposes in network reconnaissance. The culmination of the lab involved interpreting the 
				results obtained from the Intense Scan, which revealed 110 distinct tests conducted to gather comprehensive 
				information about the target network. Zenmap's discovery of six IP hosts, including the local host, provided 
				valuable insights into the network's composition and potential vulnerabilities. 
				This hands-on experience in reconnaissance and probing with common cybersecurity tools laid a strong foundation for
				understanding network security fundamentals and their practical applications.
				</p>
			<h2> Tools Used </h2>
				<p>
				In this lab, various applications and tools were employed to conduct reconnaissance and probing tasks in cybersecurity. 
				These tools included: 
				</p>
				<ul>
				<li><strong>RSA Network Investigator:</strong> RSA Network Investigator is a network forensics tool used for analyzing network traffic and detecting security incidents.
				It leverages technologies such as packet capture and analysis, deep packet inspection, and behavior analytics to identify threats and investigate security breaches. </li>
				<li><strong>Wireshark:</strong> Wireshark is a popular open-source network protocol analyzer that allows users to capture and interactively browse the traffic running on a computer network. 
				It supports various protocols and technologies, including TCP/IP, Ethernet, HTTP, and SSL/TLS, providing detailed insights into network communication. </li>
				<li><strong>Nessus:</strong> Nessus is a vulnerability scanner that helps identify potential security vulnerabilities in networks, systems, and applications. It utilizes a database of known vulnerabilities and performs various checks to assess the security posture of target assets. 
				Technologies used include vulnerability scanning, CVE database, and compliance auditing. </li>
				<li><strong>FileZilla:</strong> FileZilla is a cross-platform FTP (File Transfer Protocol) client used for transferring files between a client and a server over a network. 
				It supports FTP, FTPS, and SFTP protocols and provides a user-friendly interface for managing file transfers securely. </li>
				<li><strong>Zenmap:</strong>Zenmap is the graphical frontend for Nmap, a powerful network scanning tool used for network discovery and security auditing.
				Zenmap provides an intuitive interface for configuring and executing Nmap scans, allowing users to visualize network topology, detect open ports, and identify potential vulnerabilities.  </li>
				<li><strong>PuTTY:</strong>  PuTTY is a free and open-source SSH (Secure Shell) and telnet client used for remote access to computers over a network. It supports various protocols, including SSH, Telnet, and SCP, and offers features like session management, SSH key authentication, and tunneling capabilities. </li>
				</ul>
 </body>
</html>

<html>
	<body>
		<h1> Enabling Windows Active Directory and User Access Controls</h1>
			<h2> Overview</h2>
				<p>
				In my exploration of this project, I delved into fundamental principles of information system security. 
				Throughout the session, I grasped the significance of three critical elements crucial for an effective security
				program: Identification, Authorization, and Authentication. As I delved into practical
				applications, I learned how Authentication and access control serve as pivotal controls wielded
				by the Domain User Admin to orchestrate user accounts and resource permissions. Moreover, 
				I gained insights into the nuanced realm of access controls and permissions on Windows network 
				shares, understanding the efficacy of Security Policy-based controls like "List Folder Contents." 
				The Group Policy Editor emerged as a centralized command center for managing granular policies and permissions across the network.
				Expanding my knowledge further, I explored the concept of two-factor authentication, recognizing its role in fortifying security by requiring dual authentication methods for user access. 
				To uphold Confidentiality, Integrity, and Availability (CIA) for departmental LANs and data, I employed Windows Server Active Directory to configure access controls within the Active Directory domain partition.
				Additionally, I acknowledged the importance of safeguarding against password vulnerabilities, such as abstaining from incorporating account or username information. Through practical insights and hands-on experience, 
				this session underscored the imperative of implementing robust security measures to safeguard information systems and resources in contemporary digital landscapes.
				</p>
			<h2> Tools Used </h2>
				<p>
				In exploring "Enabling Windows Active Directory and User Access Controls," I engaged with a suite of tools and technologies essential for implementing robust security measures in Windows environments.
				These tools empower users to configure user access controls, manage permissions, and uphold the integrity of information systems. Let's delve into the tools and technologies leveraged in this endeavor:
				</p>
				<ul>
				<li><strong>Windows Active Directory:</strong> Windows Active Directory serves as the backbone for user authentication and access management in Windows environments.
				It provides a centralized database for storing user accounts, group memberships, and security policies, enabling administrators to manage network resources efficiently.  </li>
				<li><strong>Group Policy Editor:</strong> The Group Policy Editor is a powerful tool for managing granular policies and permissions across Windows networks. It allows administrators to define and enforce security settings,
				software installation policies, and other configurations for users and computers within an Active Directory environment.  </li>
				<li><strong>Two-Factor Authentication (2FA):</strong> Two-Factor Authentication enhances security by requiring users to provide two different forms of identification before granting access.
				This typically involves something the user knows (like a password) and something they possess (like a smartphone or token), adding an extra layer of protection against unauthorized access.  </li>
				</ul>
	</body>
</html>

<html>
	<body>
		<h1>Performing a Web Site and Database Attack by Exploiting Identified Vulnerabilities</h1>
			<h2>Overview</h2>
				<p>
				I conducted penetration tests in this lab on web applications and servers before their production implementation.
				This preemptive measure is essential for identifying vulnerabilities and mitigating potential risks inherent in deployment. Exploring the intricacies of cyber threats, 
				I learned about cross-site scripting (XSS) attacks, where attackers manipulate web forms to inject and execute malicious scripts, jeopardizing user data security. Additionally, I delved into reflective cross-site scripting attacks, 
				leveraging trusted user servers to execute nefarious scripts within trusted sites, presenting significant security risks. Furthermore, the lab illuminated the threat posed by SQL injection attacks, which can extract sensitive data from databases. 
				I explored security countermeasures to fortify defenses against such threats, including configuration maintenance, access restriction enforcement, and robust user authentication policies. Recognizing the critical importance of integrating penetration testing and web application testing into organizational procedures, 
				I reinforced my understanding of cybersecurity responsibilities, particularly regarding the Confidentiality, Integrity, and Availability (CIA) of production web applications and servers. Through practical exercises, I encountered various user names revealed during the inquiry, including "admin," "Gordon Brown," and "Pablo Picasso,"
				underscoring the need for vigilant identification and remediation of vulnerabilities to bolster web application and database security.
				</p>
			<h2> Tools Used</h2>
				<p>
				In this lab, titled "Performing a Web Site and Database Attack by Exploiting Identified Vulnerabilities," I embarked on a comprehensive journey into cybersecurity threats and defense mechanisms. This hands-on exploration provided invaluable insights into the intricate realm of penetration testing on web applications and servers.
				Through practical exercises, I honed my skills in proactively identifying and addressing vulnerabilities to bolster organizational security posture.
				</p>
				<ul>
					<li><strong>Penetration Testing Tools:</strong> Leveraging sophisticated tools like Burp Suite and OWASP ZAP, I simulated cyber attacks to unearth vulnerabilities in web applications and servers. These versatile tools equipped me with capabilities for scanning, intercepting, and manipulating web traffic, facilitating precise vulnerability assessment.</li>
					<li><strong>Cross-Site Scripting (XSS) Frameworks:</strong> Employing frameworks such as BeEF (Browser Exploitation Framework), I delved into the realm of cross-site scripting (XSS) attacks. BeEF empowered me to exploit browser vulnerabilities and execute malicious scripts on targeted systems, deepening my understanding of XSS vulnerabilities.</li>
					<li><strong>SQL Injection Tools:</strong> Utilizing powerful tools like SQLMap, I probed web applications and databases for SQL injection vulnerabilities. With automated detection and exploitation capabilities, SQLMap streamlined the process of identifying and extracting sensitive data from databases, enhancing my proficiency in SQL injection assessment.</li>
					<li><strong>Security Monitoring Solutions:</strong>Leveraging robust solutions like Snort or Suricata, I monitored network traffic to detect suspicious activities indicative of cyber attacks. These intrusion detection systems (IDS) offered real-time alerts and analysis, enabling proactive threat detection and response.</li>
					<li><strong>Operating Systems:</strong> I navigated the cybersecurity landscape using operating systems like Kali Linux, renowned for its arsenal of pre-installed tools tailored for penetration testing and ethical hacking. Kali Linux provided a robust platform for conducting security assessments and forensic analysis, amplifying my capabilities in cybersecurity exploration.</li>
					<li><strong>Web Application Frameworks:</strong> Engaging with platforms like Damn Vulnerable Web Application (DVWA), I immersed myself in creating and exploiting intentionally vulnerable web applications. DVWA offered a controlled environment for practicing the exploitation of common web application vulnerabilities, fostering practical vulnerability assessment and mitigation skills.</li>
				</ul>
	</body>
</html>

<html>
	<body>
	<h1>Eliminating Threats with a Layered Security Approach</h1>
		<h2>Overview</h2>
			<p>
			I studied cybersecurity strategies to fortify organizational defenses against various threats in this project. Through a layered security approach,
			I delved into the nuances of malware mitigation, encryption techniques, and network traffic filtering to safeguard information systems from potential breaches. 
			Here's a breakdown of critical insights gained from the lab:
			</p>
				<ol>
					<li><strong>Differentiating Between Virus and Trojan:</strong>  I elucidated the main difference between a virus and a Trojan, drawing parallels to the Greeks' deception of the Trojans in Homer's Iliad. Unlike viruses, Trojans rely on user interaction to execute malicious code, underscoring the importance of user awareness in combating cyber threats.</li>
					<li><strong>Impact of Malware on Information Systems Security:</strong> I explored how malware attacks can compromise the confidentiality, integrity, and availability of information systems. Malicious software can breach confidentiality by accessing restricted data, compromise integrity by modifying information, and disrupt availability by causing system disturbances or slowdowns.</li>
					<li><strong>Importance of Antivirus Signature Updates:</strong> I recognized the significance of updating antivirus signature files to protect against evolving malware threats. By ensuring that antivirus software is equipped with the latest threat definitions, organizations can enhance their defense mechanisms against emerging cyber threats.</li>
					<li><strong>Utilizing Encryption for Email Attachments:</strong> I learned about the benefits of encrypting archive files before emailing them, as encrypted files are immune to detection by antivirus scans. This precautionary measure enhances data confidentiality and minimizes the risk of unauthorized access during file transmission.</li>
					<li><strong>Network Traffic Filtering with Windows Firewall:</strong> Exploring the capabilities of Windows Firewall with Advanced Security, I discovered its ability to filter both inbound and outbound application traffic, including system services. This feature enables organizations to control network access and mitigate the risk of unauthorized data transfers.</li>
					<li><strong>Indicators of Compromised Systems:</strong> I identified typical signs indicating a compromised computer system, such as missing data, sluggish program performance, or system-wide malfunctions. Recognizing these indicators is critical for prompt detection and remediation of security breaches.</li>
					<li><strong>Workstation Domain Policy for Antivirus Software:</strong>  I outlined the elements required in a workstation domain policy regarding the use of antivirus and malicious software prevention tools. This policy should define terms, emphasize the importance of software implementation for protecting organizational assets, specify authorized personnel for software management, and delineate consequences for policy violations.</li>
				</ol>
			<p>
			Through hands-on exercises and theoretical insights, this lab equipped me with a base knowledge and skills to implement a layered security approach and effectively mitigate cybersecurity risks. This experiential learning experience deepened my understanding of cybersecurity principles and enhanced my readiness to navigate the evolving threat landscape.
			</p>
		<h2>Tools Used</h2>
			<p>
			In the lab, "Eliminating Threats with a Layered Security Approach," I explored cybersecurity strategies to fortify organizational defenses against evolving threats. Through hands-on exercises and theoretical insights, I delved into malware mitigation, encryption techniques, and network traffic filtering intricacies. Here's a curated list of the tools, technologies, and operating systems that I utilized in this immersive learning experience:
			</p>
			<ul>
			<li><strong>Antivirus Software:</strong> Leveraging robust antivirus solutions, I ensured the protection of information systems against malware threats by detecting and eliminating malicious software.</li>
			<li><strong>Encryption Tools:</strong> Employing encryption tools, I fortified data confidentiality by encrypting sensitive information, preventing unauthorized access during transmission or storage.</li>
			<li><strong>Windows Firewall with Advanced Security:</strong> Exploring the capabilities of Windows Firewall with Advanced Security, I controlled network traffic by filtering both inbound and outbound application traffic, enhancing network security.</li>
			<li><strong>Malware Analysis Tools:</strong> Utilizing malware analysis tools, I dissected and analyzed malicious software to understand its behavior and characteristics, aiding in the development of effective mitigation strategies.</li>
			<li><strong>Email Encryption Solutions:</strong>Employing email encryption solutions, I secured email communications by encrypting attachments and messages, safeguarding sensitive information from interception or unauthorized access.</li>
			<li><strong>Network Monitoring Solutions:</strong>Leveraging network monitoring solutions, I monitored network traffic to detect suspicious activities and potential security breaches, enabling proactive threat detection and response.</li>
			<li><strong>Operating Systems:</strong>Navigating the cybersecurity landscape, I utilized operating systems such as Windows and Linux, leveraging their diverse capabilities and functionalities to implement layered security measures effectively.</li>		
			</ul>
	</body>
</html>
