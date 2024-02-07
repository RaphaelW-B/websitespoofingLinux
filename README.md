<h1>Credential Harvesting Tool via Spoofing in Linux</h1>


The objective of this training lab is to better understand how credential harvest can take place.  Credential harvesting involves gathering sensitive data like passwords or credit card details from a target without their knowledge. Kali Linux is the designated tool for this exercise, providing users with hands-on experience in Linux-based operations. The lab's primary purpose is educational, and an opportunity to develop skills in Linux navigation and techniques in a controlled setting conducive to learning.

<h2>The project leverages the following skills:</h2>

<b>Technical Skills:</b>

- Kali Linux, a specialized distribution for penetration testing and digital forensics.
- Understanding of command-line interface (CLI) operations in Linux environments.
- Familiarity with networking concepts, including IP addressing and network communication protocols.
- Knowledge of web browsers and basic web navigation.

<b>Cybersecurity Skills:</b>

- Understanding of social engineering techniques used for exploiting human behavior to gain unauthorized access to systems or data.
- Familiarity with credential harvesting methods and associated attack vectors.
- Awareness of phishing attacks and techniques, including website cloning.
- Ability to identify and analyze potential security risks and vulnerabilities in web applications and systems.

<b>Analytical Skills:</b>

- Capacity to interpret and analyze data collected during the credential harvesting process, such as POST requests and user interaction with cloned websites.
- Ability to identify patterns and anomalies in network traffic and user behavior.

<h3>Task 1: Launch Kali Linux and HiddenEye</h3>

- Begin by starting your virtual machine and initiating Kali Linux. This task is completed within an Azure virtual machine, which I utilize for various lab exercises.

<p align="center">
<img src="https://i.imgur.com/UWqWhkp.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

- Access the terminal and execute HiddenEye.

<p align="center">
<img src="https://i.imgur.com/ISg2uv4.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h3>Task 2: Navigate to Website Attack Vectors Menu</h3>

- Select the vector and the operation mode:
  
<p align="center">
<img src="https://i.imgur.com/K06RIKN.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

- Select the page to which the user will be redirected after informing his credentials:

<p align="center">
<img src="https://i.imgur.com/IXebv9n.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

- Copy the generated URL:

<p align="center">
<img src="https://i.imgur.com/ZbrdFXd.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>


<h3>Task 3:Harvest Credentials</h3>

- Upon accessing the site, interact with the cloned login page by entering random credentials into the provided fields and clicking on the "Log In" button.

<p align="center">
<img src="https://i.imgur.com/RKegTmH.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

- Credentials were succesfully harvested.

<p align="center">
<img src="https://i.imgur.com/rJ0lcXP.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
