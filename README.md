# Understanding-Zero-Trust

This paper introduces the 7 Pillars and 7 Elements of the Zero Trust security model, a modern approach that assumes no user, device, or application should be trusted by default, even within internal network perimeters. The goal is to enforce strict verification, or "never trust, always verify," throughout an organization.

<p align="center"><strong>Zero Trust: 7 Pillars and 7 elements</strong></p>
  

The elements and pillars of zero trust are crucial to understand for the implementation within an organization. I have used roman numerals for the pillars of zero trust and a numbered list for the elements. I will also provide a short description of what these are and what they mean within the organization. There is some overlap between the pillars and elements and in those cases I will provide a shorter description.

<p align="center"><strong>Pillars</strong></p>

- **Users:** Who is accessing the resources or environment? How do you know it is them? These questions help with defining what is needed for this element. Authenticating and authorization is needed for users accessing the environments and services. This can be with credentials along with Multifactor Authentication or Single Sign on methodologies. Once the user is signed in they will and should only have access to what they need in order to do their job or work needed. Permission is needed for any other resources needed and even then, it should be looked at in terms of if it is needed indefinitely or temporarily to accomplish the assigned work.

- **Devices:** These need to be in compliance with policies and guidelines. They must adhere to security postures and acceptable use policies. They should be patched and updated regularly. 

- **Network and Environments:** These should be secured and broken down to micro-segmented networks and implement encryption. They should be behind a firewall or other trust broker application or service. It should have monitoring and log aggregation that allows nonrepudiation so that actions taken can be shown and unauthorized or malicious activity can be proven.

- **Applications and Workloads:** You can whitelist or blacklist applications which will help keep only authorized applications used in the workplace. You can also implement a web application firewall that will help secure and permit allowed resources. 

- **Data Security:** Data encryption, tagging, logging, and access controls should be in place for data in rest and in transit. 

- **Analytics and Visibility:** Continuous monitoring and logging should be used and analyzed for security purposes. 

- **Automation and Orchestration:** This will help streamline the implementation of a Zero Trust model across the organization and help lessen human error. 

<p align="center"><strong>Elements</strong></p>

- **Who is connecting:** This is similar to the first pillar of the Zero Trust model Users.

- **What are the attributes:** The Users pillar overlaps into this with the permissions needed.

- **Where is the connection going:** This element implements multiple pillars by validating the user, has access to the right permissions, will have access to devices and networks, and will likely access applications and services. 

- **Assess risk using context:** What risks are possible and are there any threats that are present.

- **Prevent compromise:** Blocking malicious activities, actions, and content. 

- **Prevent data loss:** Analyzing data that is traveling through or out of the network and blocking the passage of sensitive data from leaving the network. 

- **Enforce policy:** All the elements must pass through this element first. If the user is not allowed the policy should block the user. If the data is not permitted to leave the network, it should be blocked. Blacklisted applications should not be accessed and so on.

<p align="center"><strong>How Zero Trust Can Be Used in the Company</strong></p>

Zscaler can be used in the company to secure, authenticate, segment, analyze, and monitor. This would help improve security and lower the attack surface. This will not be a full zero trust model, but it would satisfy several elements and pillars.

<p align="center"><strong>Summary</strong></p>

While Zscaler provides a robust Zero Trust model itself, there are still things we would need to implement. Yes, Zscaler will provide Zero Trust, but no, we still need to provide a little more to have full Zero Trust. You can use device monitoring that will protect individual devices and local accounts. You will also need to implement employee training and make it known what zero trust is, why it’s important, and to report any issues or vulnerabilities. 

<p align="center"><strong>References</strong></p>

The CISO Perspective. (2022). What is Zero Trust Network Access (ZNTA)? The Zero Trust Model, Framework and Technologies Explained. [YouTube Video](https://youtu.be/DLQAbJm4gFM?si=T0cuQSixnFRlrTGe)

NextDLP. Florkey, Christina. (2024). What are the 7 pillars of Zero Trust. [Website](https://www.nextdlp.com/resources/blog/7-pillars-of-zero-trust)

Zscaler Inc. Seven Elements of Zero Trust. [Website](https://www.zscaler.com/resources/seven-elements-of-zero-trust)

Zscaler Inc. (2022). The Zscaler Tech Sessions: Seven Elements of Zero Trust. [YouTube Video](https://youtu.be/btlf_4v3EY0?si=hWvM2bS7piPD-NHG)
