In this assignment, we will delve into the fascinating world of cybersecurity by simulating and defending against cyberattacks. Our primary objective is to develop a comprehensive repository that encompasses the entire process of emulating a known Threat Actor (TA), creating effective detection or prevention mechanisms, and testing them on a system. This repository is a crucial part of our learning journey in COIT11241 CyberSecurity Technologies.

Purpose of the Repository:

The purpose of this repository is threefold:

Emulate an Attack: We will spend five hours designing and executing a series of attacks that closely mimic the actions of the infamous BlackCat ransomware. By researching and identifying actual commands used by BlackCat, we aim to create PowerShell scripts that emulate these attacks as realistically as possible. We'll document our sources, categorize these attacks using the ATT&CK framework, and ensure the code's functionality, modularity, style, and documentation meet high standards.

Implement and Test Detections or Preventions: After emulating the attacks, we will dedicate the next five hours to developing detection or prevention mechanisms. These mechanisms should identify and respond to our simulated attacks effectively. We'll focus on creating rules within Wazuh, which will generate alerts when the attacks are executed. Our goal is to strike a balance between specificity and noise in our alerts, ensuring they are practical and actionable. Alternatively, we can opt to implement prevention measures and demonstrate the difference in attack behavior when these measures are in place.

Repository Management: To facilitate collaboration and transparency, we will create a private Git repository. This repository will serve as a centralized hub for all our project files, including attack scripts, detection/prevention rules, documentation, and testing results. We will invite our tutor, the unit coordinator, and fellow group members to access this repository, ensuring that all group members contribute and collaborate effectively.

Contents of the Repository:

Our repository will include the following key components:

Attack Scripts: These scripts will emulate the BlackCat ransomware attacks, closely following real attack commands. Each script will be well-documented, formatted, and supported by evidence of development through Git commits.

Detection or Prevention Rules: We will provide detailed rules for Wazuh that trigger alerts or prevent attacks. These rules should strike the right balance between specificity and noise, ensuring that they are effective in identifying or mitigating attacks.

Testing Results: To validate the effectiveness of our detections or preventions, we will include testing results, demonstrating how our mechanisms respond to the simulated attacks.

Documentation: Our repository will contain comprehensive documentation, including references to the sources used for attack emulation, categorization of attacks using ATT&CK, and detailed explanations of detection or prevention rules.

Presentation Slides: We will create PowerPoint slides summarizing our attacks, detection/prevention mechanisms, and testing results. These slides will be included in our repository and shared during our final Assignment 3 presentation.

By maintaining this well-organized repository, we aim to showcase our understanding of cybersecurity technologies and our ability to defend against real-world threats effectively.
