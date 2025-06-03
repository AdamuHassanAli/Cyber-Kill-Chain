# Cyber Kill Chain Lab
<b>Platform:</b> TryHackMe | <b>Type:</b> Hands-on Lab | <b>Focus:</b> Adversary Behavior Analysis, Attack Lifecycle, Threat Detection
<h2>Overview:</h2>
In this lab, I explored the Cyber Kill Chain, a model developed by Lockheed Martin to describe the structured progression of a cyberattack. The room breaks down the attack lifecycle into seven distinct phases:
<li><b>Reconnaissance</b>– Gathering intelligence on targets through passive and active methods</li>
<li><b>Weaponization</b>– Crafting malicious payloads to exploit discovered vulnerabilities</li>
<li><b>Delivery</b> – Transmitting payloads via phishing, malicious links, or infected USBs</li>
<li><b>Exploitation</b> – Executing the malicious code on a victim's system</li>
<li><b>Installation</b> – Deploying malware or backdoors for persistent access</li>
<li><b>Command and Control (C2)</b> – Establishing remote control channels to the victim system</li>
<li><b>Actions on Objectives</b> – Performing the attacker’s end goals, such as exfiltration or destruction</li>

<h2>What I Learned:</h2>
<li>How each stage of the Cyber Kill Chain builds on the previous to form a complete attack path</li>
<li>How to recognize real-world attacker behaviors at each phase of an intrusion</li>
<li>The importance of disrupting attacks early in the chain to reduce damage</li>
<li>How SOC analysts map observed indicators of compromise (IOCs) to specific stages</li>
<li>The value of Kill Chain analysis in threat hunting, blue teaming, and incident response</li>
<li>Limitations of the Kill Chain and how newer frameworks (like MITRE ATT&CK) complement it</li>

<h2>Skills Gained:</h2>
<li>Adversary TTP (Tactics, Techniques, Procedures) mapping</li>
<li>Threat modeling and attack lifecycle comprehension</li>
<li>Kill Chain-based incident detection and response</li>
<li>Application of defense-in-depth strategies</li>
<li>Cyber threat intelligence interpretation</li>
<li>SOC-aligned analysis and reporting</li>

# Paractical Scenario
<b>Platform:</b> TryHackMe | <b>Type:</b> Practical Scenario | <b>Focus:</b> Incident Analysis, Cyber Kill Chain
<h2>Summary:</h2>
This hands-on exercise involved analyzing one of the most significant real-world data breaches — the 2013 Target cyber-attack, which affected approximately 40 million credit and debit card accounts. The exercise aimed to apply my knowledge of threat analysis by reconstructing the attack using the Cyber Kill Chain framework.

<h3>Key Objectives:</h3>
<li>Understand how the breach occurred and progressed across the attack lifecycle</li>
<li>Apply theoretical knowledge in a practical lab environment</li>
<li>Identify and classify attacker tactics and techniques in each phase of the Kill Chain</li>
<li>Use a static site to input findings and receive instant feedback</li>

<h2>What I Did:</h2>
I deployed a static site lab environment where I reconstructed the Target attack by mapping attacker actions to each phase of the Cyber Kill Chain. I identified the following techniques and correctly aligned them:<br>
<li><b>Reconnaissance</b> -Fill not required</li>
<li><b>Weaponization</b> – PowerShell</li>
<li><b>Delivery</b> – Spearphishing attachment</li>
<li><b>Exploitation</b> – Exploit public-facing application</li>
<li><b>Installation</b> – Dynamic linker hijacking</li>
<li><b>Command and Control (C2)</b> – Fallback channels</li>
<li><b>Actions on Objectives</b> – Data from local system</li>
<br>

<img src="https://github.com/AdamuHassanAli/Cyber-Kill-Chain/blob/main/Images/Cyber%20Kill%20Chain%20Answer.jpeg?raw=true"/>
<br>


<b>Here is the catched flag</b>

<br>
<img src="https://github.com/AdamuHassanAli/Cyber-Kill-Chain/blob/81b561f7725d90a9fa8e6c93b117956c635c818d/Images/Cyber%20Kill%20Chain%20CTF.jpeg "/>

<h3>Outcome:</h3>
This exercise strengthened my incident analysis and threat modeling skills. I gained a practical understanding of how advanced persistent threats (APTs) operate in real-world scenarios and how organizations can map such attacks using frameworks like the Cyber Kill Chain to improve their detection and response strategies.
