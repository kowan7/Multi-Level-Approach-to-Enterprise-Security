# Multi-Level-Approach-to-Enterprise-Security
<h1>Multi-Level Approach to Enterprise Security</h1>

<h2>Description</h2>
I successfully completed this project while enrolled in the CYB420 Enterprise Security course at Southern New Hampshire University.
<br />
<br />
<b>Overview</b> 
<br />
<br />
When taking a multi-layered approach to building a comprehensive security infrastructure, you need to think in detail about the risk domains of people, processes, and technology. Use your adversarial mindset to put yourself in the position of someone attacking your organization, and ask yourself where the weakest areas are. It will also be useful to keep in mind all the pillars of the confidentiality, integrity, and availability (CIA) triad in order to point out vulnerabilities and brainstorm solutions that can be implemented in the context of each.

As you have often done throughout this program, you will want to engage in a systems thinking mindset in order to make assessments at the enterprise level. Many resources on this topic have already been saved in your playbook, and you can also reference the National Institute of Standards and Technology (NIST) enterprise security frameworks as you develop your approach. When looking at infrastructure diagrams and assets, walk yourself through the whole building as a mental exercise. Follow the step-by-step process of normal, daily operational tasks and look at each component of the system as one piece of a larger puzzle. For example, consider walking through the front door and heading to your desk. How are the risk domains of people, process, and technology involved in that simple action?

Remember, there is not going to be one solution to fit all possible outcomes, and you will have to customize your strategies to match the needs and circumstances of the environment. This will be particularly important when looking to the future because what works well today may not always scale as intended. Think about how challenging it is to envision the ways adversarial tools will be different in 10 years. The best predictions you can make are based on the most advanced strategies you have at this time. Use what you know to take a proactive approach in building technology and processes to answer for threats that may arise in the future. Doing this will also allow you to maximize the return on investment, which will be useful when you transition to conceptualizing plans and budget while continuing in this course.

In this assignment, you will demonstrate your mastery of the following competencies:

Design and implement a layered, technical security solution to meet organizational requirements
Develop appropriate controls to counteract adversaries and protect organizational assets

<b>Scenario</b> 

You are a security analyst working for the ACME Company, which is preparing for a future transition into a new market. This evolution will allow the company to pick up contracts with the federal government over the next seven years. A change in infrastructure must be completed in order to grow external confidence in the organization’s security posture. Performing assessments now will allow company leadership to plan for how they will meet compliance in the future and budget for the expense of new technology or processes that may need to be introduced.

The ACME Company is looking to implement a multi-layered approach to security that considers the three risk domains of people, process, and technology. In addressing these, the most important considerations for the organization will be to include better physical security, implement granular access controls, isolate networks, shape internal and external IP traffic, and implement better security coverage for all workstations and servers. There will be more specific requirements that the organization will need to meet in order to become an authorized government contractor in the future, but the assessment you have been tasked with today will begin the first steps toward improving the organization’s enterprise security.

<b>Prompt</b> 

You will be charged with performing an assessment by referencing the Project One Inventory of Organization Hardware and the Project One Current Organization Infrastructure Diagram, both of which are linked in the assignment in Module Four of your course. Upload the Project One Current Organization Infrastructure Diagram file to the Virtual Lab and open the file in Packet Tracer

<h2>Inventory of Organization Hardware PDF</h2>

![image](https://github.com/kowan7/Multi-Level-Approach-to-Enterprise-Security/assets/143843214/98f9b6b2-df95-4892-be54-915846ede5a4)

<h2>Current Organization Infrastructure Diagram </h2>
<h2>Packet Tracer File</h2>

![image](https://github.com/kowan7/Multi-Level-Approach-to-Enterprise-Security/assets/143843214/7daf5ecc-d158-4022-8f0f-aafb36f5d513)

<h2>You must address the critical elements listed below.</h2>

<b>Threat Assement</b> 

<b>Apply system thinking to identify at least two vulnerabilities in the risk domain of people.</b> 

People (Vulnerability)

1.	Lack of security Awareness training: ACME's absence of security awareness training heightens the risk of phishing attacks, potentially leading to unauthorized access and data breaches. This deficiency also raises concerns about insider threats and contributes to a sluggish response to security incidents due to a lack of awareness about protocols, leaving the organization exposed to prolonged risks. The overarching issue is the potential development of a weak security culture at ACME, where employees may lack responsibility for maintaining a secure environment, posing risks of reputational damage and legal consequences.

   
2.	Inadequate Access Controls for Physical Spaces: The vulnerability stemming from inadequate access control for physical spaces, specifically the absence of locks on the IT equipment room doors, poses a critical threat to the overall physical security of ACME. Without proper access controls, unauthorized personnel could potentially gain entry to the IT equipment room, exposing sensitive infrastructure and data to the risk of tampering or theft. This deficiency compromises the confidentiality and integrity of the organization's IT assets.
   
<b>Apply systems thinking to identify at least two vulnerabilities in the risk domain of process.</b> 

Process (Vulnerability)

1.	Lack of Network Segmentation: The vulnerability stemming from the lack of network segmentation, specifically the absence of Virtual Local Area Networks (VLANs), poses a critical security risk for ACME. Network segmentation, achieved through VLANs, is crucial for isolating different parts of the infrastructure, preventing lateral movement in the event of a security breach. Without this protective measure, unauthorized access to one segment of the network could lead to unrestricted movement throughout the entire system, potentially compromising sensitive information. Moreover, for enhanced security, it is imperative to isolate authorization servers from the internal network. Implementing VLANs and isolating authorization servers are essential steps to fortify ACME's security, preventing unauthorized access and containing potential security breaches effectively.

   
2.	Absence of VPN for Remote Employees: The vulnerability arising from the absence of a Virtual Private Network (VPN) for remote employees represents a significant security risk for ACME. Remote employees accessing internal resources lack the protection of a VPN, exposing the organization to potential data interception. Without the encrypted tunnel provided by a VPN, sensitive information transmitted between remote employees and internal resources is vulnerable to interception by malicious actors. This lack of secure communication channels jeopardizes the confidentiality and integrity of the data being accessed remotely. 

<b>Apply systems thinking to identify at least two vulnerabilities in the risk domain of technology.</b> 

Technology (Vulnerability)
1.	Use of hubs instead of Switches: The vulnerability arising from the utilization of hubs rather than switches in ACME's network infrastructure poses a significant security risk. Hubs broadcast data indiscriminately to all connected devices, increasing the susceptibility to eavesdropping and unauthorized access. This broadcast nature not only compromises the confidentiality of transmitted information but also contributes to network congestion. As data is broadcasted to all devices, the network experiences increased traffic, potentially leading to congestion and performance issues.

   
2.	Unsecured Authentication Server: The vulnerability associated with an unsecured authentication server in ACME's infrastructure represents a critical security concern. The absence of isolation for the authentication server exposes it to direct attacks, posing a significant risk to the overall security of the organization. Without proper isolation measures, malicious actors could exploit vulnerabilities in the authentication server, potentially leading to unauthorized access, data breaches, or compromise of sensitive information. The lack of a protective barrier leaves the authentication server susceptible to various forms of cyber threats, including direct targeted attacks aimed at exploiting vulnerabilities within the server itself. 

<b>Adversarial Mindset</b>

<b>Discuss how to employ an adversarial mindset when assessing vulnerabilities in the risk domain of people.</b>

<b>People</b>

When employing an adversarial mindset to assess vulnerabilities in the people domain at ACME, particularly focusing on the lack of security awareness training and inadequate access controls for physical spaces, strategic approaches can be implemented. Firstly, conduct simulated phishing attacks to gauge employees' susceptibility to email-based threats, considering the potential risks of unauthorized access due to inadequate security awareness. Craft realistic scenarios mimicking common phishing tactics and analyze responses to identify areas for improvement. Additionally, implement social engineering exercises to assess employees' resistance to manipulation, simulating situations where individuals may unwittingly compromise security, including physical access control measures. Continuously refine and update these adversarial simulations based on evolving cyber threats and physical security considerations to ensure ongoing effectiveness. By adopting this adversarial mindset, ACME can proactively address vulnerabilities, enhance both digital and physical security awareness, and foster a more resilient security culture within the organization.



<b>Discuss how to employ an adversarial mindset when assessing vulnerabilities in the risk domain of process.</b>

<b>Processes</b>

When employing an adversarial mindset to assess vulnerabilities in the process domain at ACME, particularly focusing on the lack of network segmentation and the absence of a VPN for remote employees, several strategic approaches can be adopted. Firstly, simulate potential security breaches by envisioning scenarios where unauthorized access occurs due to the absence of network segmentation. Evaluate the organization's response to these simulated incidents, identifying weaknesses in the process of containing and mitigating security breaches. Additionally, conduct adversarial testing on the remote access process by simulating potential data interception scenarios. This involves creating situations where remote employees access internal resources without the protection of a VPN, mimicking the conditions that could lead to data compromise. By adopting an adversarial mindset in these assessments, ACME can proactively identify vulnerabilities in its processes, refine security measures, and enhance the overall resilience of its network infrastructure and remote access protocols.

<b>Discuss how to employ an adversarial mindset when assessing vulnerabilities in the risk domain of technology.</b>

<b>Technology</b>

In the realm of technology vulnerabilities at ACME, the use of hubs instead of switches poses a security risk by allowing indiscriminate data broadcasting, potentially leading to eavesdropping and unauthorized access. This broadcast nature also contributes to network congestion. Simulating adversarial scenarios is key to assessing the organization's response to these vulnerabilities. Furthermore, the unsecured authentication server vulnerability exposes ACME to direct attacks, making it crucial to simulate potential threats, test existing security measures, and continuously refine these simulations based on evolving cyber threats. Employing an adversarial mindset in technology assessments enables ACME to proactively identify and address weaknesses, ultimately fortifying the organization's overall security posture.

<b>Infrastructure Diagram</b>

<b>Implement at least two appropriate controls to address identified vulnerabilities in people.</b>

<b>Implement at least two appropriate controls to address identified vulnerabilities in process.</b>

<b>Implement at least two appropriate controls to address identified vulnerabilities in technology.</b>

<b>The diagram below illustrates the implemented controls to address vulnerabilities in human factors, fortify organizational processes, and mitigate technological vulnerabilities in order to enhance Acme's security posture.</b>

![image](https://github.com/kowan7/Multi-Level-Approach-to-Enterprise-Security/assets/143843214/2eb00e5d-1327-45f6-9f8d-9d33b40edeea)

<b>These items I was unable to add to the packet tracer diagram but are very important to Acme's security Posture.</b>

-	Deploy a VPN site to site Remote Employee access solution
-	Enable Multi-Factor Authentication to the following systems:
  
o	Authentication Server

o	Site-to site VPN solution

o	HR and finance system

o	Records System

o	IT Dept. Workstations


<b>Organizational Protection</b>

<b>Explain how the implemented controls will counteract adversaries and protect organizational assets in the risk domain of people.</b>

<b>People (Counteractions)</b>

To address vulnerabilities in the "People" domain, the implementation of security awareness training and biometric access controls serves as a comprehensive counteraction strategy. Regular and engaging security awareness programs are crucial in educating employees on recognizing and mitigating cybersecurity threats such as phishing attacks and social engineering tactics. This heightened awareness contributes to a more informed and security-conscious workforce. Simultaneously, the integration of biometric access controls, utilizing methods like fingerprint or retina scans, provides an additional layer of secure authentication, mitigating risks associated with unauthorized access. The synergy between these counteractions not only enhances the organization's defense against insider threats but also cultivates a robust security culture, reinforcing the importance of individual responsibility in safeguarding sensitive information and maintaining a secure environment.

<b>Explain how the implemented controls will counteract adversaries and protect organizational assets in the risk domain of process.</b>

<b>Process (Counteraction)</b>

To fortify the vulnerabilities within the "Process" domain, the recommended counteractions involve the implementation of Virtual Local Area Networks (VLANs) and Virtual Private Network (VPN) solutions. VLANs are introduced to segment and isolate different segments of the network, mitigating the risk of lateral movement in case of a security breach. This segmentation ensures that unauthorized access in one network segment does not lead to unrestricted movement across the entire system, thereby limiting the potential impact of security incidents. Simultaneously, VPN solutions are deployed to establish secure connections for remote employees accessing internal resources. This ensures encrypted and protected data transmission over the internet, addressing the vulnerability associated with the absence of a VPN for remote employees. Together, these counteractions create a comprehensive defense strategy, enhancing internal network security, limiting lateral threat progression, and providing secure remote access to critical processes and data.

<b>Explain how the implemented controls will counteract adversaries and protect organizational assets in the risk domain of technology.</b>

<b>Technology (Countermeasure)</b>

To bolster the security posture within the "Technology" domain, ACME should implement a series of counteractions. First, replacing hubs with switches in the network infrastructure enhances data transmission security by intelligently directing data to specific devices, reducing the risk of eavesdropping and unauthorized access. Second, the introduction of network segmentation through Virtual Local Area Networks (VLANs) isolates different segments, preventing lateral movement within the network and restricting the potential impact of security breaches. Third, isolating the authentication server from the internal network establishes a protective barrier, safeguarding it against direct attacks and mitigating the risks associated with unauthorized access and data breaches. Collectively, these counteractions contribute to an overall improvement in the security posture of ACME's technological infrastructure, addressing vulnerabilities related to hubs, unsecured authentication servers, and unauthorized access effectively.

<b>Discuss how to balance the implementation of controls between simple fixes and organizational concerns.</b>

<b>Balancing Implementation</b>

Prioritize implementation based on risk severity. Address critical vulnerabilities with immediate, simple fixes while planning for more comprehensive, long-term solutions to align with organizational goals and resources. Regularly reassess and update controls to adapt to evolving threats and technologies.

<b>Conclusion:</b>

In conclusion, the multifaceted approach outlined in this proposed Acme protection strategy underscores the significance of addressing vulnerabilities across the "People," "Process," and "Technology" domains. By implementing comprehensive counteraction strategies, such as security awareness training and biometric access controls for the "People" domain, Virtual Local Area Networks (VLANs) and Virtual Private Network (VPN) solutions for the "Process" domain, and a series of technological countermeasures for the "Technology" domain, ACME aims to fortify its security posture and meet regulatory requirements. This holistic defense strategy not only enhances protection against insider threats, lateral movements, and unauthorized access but also fosters a security-conscious culture within the organization. Moreover, the recommended approach of prioritizing counteraction implementation based on risk severity, alongside continuous reassessment and updates, ensures a dynamic and adaptive security framework aligned with ACME's organizational goals and resources.

<b>References:</b>

<b>Comptia Network+ (N10-008) full course & practice exam</b> 

<b>  udemy. (n.d.). https://www.udemy.com/course/comptia-network-n10-008/</b>

<b>Comptia security+ complete training course & practice exam</b>

<b>udemy. (n.d.-b). https://www.udemy.com/course/securityplus/</b> 

<br />
<br />
<h2>The End</h2>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
