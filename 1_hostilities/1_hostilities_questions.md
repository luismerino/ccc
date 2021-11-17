# Module 1. Hostilities in Cyberspace

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg


This module of the course on [Cybercrime, Cyberespionage and Cyberconflicts](https://github.com/0xjet/ccc) examines the topic of why cyberspace is such a hostile environment. It provides a short introduction to the history of the Internet and its major themes. It then discusses types of threats and abuse (the _what_), opponents (the _who_) and their intent (the _why_). The module concludes with a debate on how we got here and why security is hard.


**Learning Outcomes**
* Understand the history and development of the Internet and its security and privacy problems.
* Recognize different types of security incidents as classified by taxonomies used by CSIRTs.
* Know the different types of opponents and their intent, motivations, and means.
* Discuss and analyze the technical, legal, and ethical challenges relating to security and privacy in cyberspace.


## Contents and Readings

1. History of the Internet
    * Barry M. Leiner, Vinton G. Cerf, David D. Clark, Robert E. Kahn, Leonard Kleinrock, Daniel C. Lynch, Jon Postel, Lawrence G. Roberts, Stephen Wolff. [A Brief History of the Internet](https://sites.cs.ucsb.edu/~almeroth/classes/F10.176A/papers/internet-history-09.pdf). ACM SIGCOMM Computer Communication Review, Volume 39, Number 5, October 2009.
    * Robert H. Zakon. [Hobbes' Internet Timeline 25](https://www.zakon.org/robert/internet/timeline/).
    * Internet Society's [A Short History of the Internet](https://www.internetsociety.org/internet/history-internet/) series.
2. Types of Threats
    * ENISA. [Reference Incident Classification Taxonomy](https://www.enisa.europa.eu/publications/reference-incident-classification-taxonomy).
    * Europol. [Common Taxonomy for Law Enforcement and CSIRTs](https://www.europol.europa.eu/publications-documents/common-taxonomy-for-law-enforcement-and-csirts).
3. Opponents
    * Ross Anderson. _Security Engineering, 3rd Edition_. [Chapter 2: Who is the Opponent?](https://www.cl.cam.ac.uk/~rja14/book.html)
4. Why Security is Hard
    * No mandatory reading


## Slides

The slides used in class for this module are available [here](https://tbd).


## Questions

### Q1. Classifying security incidents
Read this [ENISA note](https://github.com/enisaeu/Reference-Security-Incident-Taxonomy-Task-Force/blob/master/Documentation/howtogetstarted.md#multiple-values) on classifying incidents with multiple values. Assign classification label(s) to the following incidents using both the ENISA and Europol taxonomies.

1. A security administrator discovers port scanning traces in a network log.
2. Some employees receive an email with a malicious Microsoft Word document attached. The emails are personalized, i.e., they address the employees by their name and contain other pesonal details.
3. A social network user posts links to websites devoted to cruelty towards animals.
4. The phone of a 15 years old kid is running a parental control app that allows parents to monitor Internet usage and read all conversations in messaging apps.
5. A network intrusion detection system stops an attempt to exploit a known vulnerability against a web server.
6. A web application firewall (WAF) detects a SQL injection attack.
7. After a successful intrusion into a server, an attacker exploits a vulnerability to elevate privileges and compromises the administrator (root) account.
8. An attacker exploits a known security vulnerability in an unpatched web server and then uses it to distribute copyright-protected ebooks.
9. A router contains is found to contain a hardcoded password for a privileged account.
10. As part of a ransomware campaign, attackers exfiltrate confidential company data to their servers and then encrypt all company systems, rendering them unusable. They demand a ransom and threaten to publish the data for free if they do not receive payment in a few days.
11. A security administrator discovers that some computers in the network are running a bot that is used to launch DDoS attacks.
12. Someone has installed a rogue access point and is sharing the corporate network through it.
13. An attacker with access to a privileged account installs in some compromised machines a TLS certificate that facilitates traffic interception by deploying a transparent proxy.
14. A user receives an email pretending to come from a bank. The email states that a money transfer has been ordered and asks the user to click on a link to complete or cancel the process. The link points to a site aimed at stealing user credentials.
15. A user receives a text message (SMS), presumably from a courier, about a parcel that is about to be delivered. The message contains a shortened URL that points to an Android app that is downloaded and installed (with user consent). The app is a banking trojan.

### Q2. Usability and security
Give an example of a usability failure that is at the root of a security incident. Discuss the trade-offs (if any) made by the designers when considering usability vs. security.

### Q3. Content moderation
Consider the case of a social network or a video streaming platform that is forced to moderate user submissions to reduce the spread of disinformation campaigns and potentially harmful content. Discuss the incentives that the platform has (not) to do it. Enumerate some of the technical complications that involve doing this at scale.

### Q4. Incentives to develop and maintain secure products
Discuss the incentives that a software manufacturer has to care about the security of its products, i.e., to consider security aspects during the development lifecycle, to do security audits on the code, to keep an eye on vulnerabilites of components your products depend on, and to maintain fluid communication channels with security researchers that report vulnerabilities).

### Q5. Impact of a security incident
Describe at least 4 factors that affect the impact (criticality) level of a security incident. Provide a short rationale of your answer for each factor.

### Q6. Compare and contrast: ransomware vs. cyberespionage
Do a comparative analysis of a global ransomware campaign vs. a cyberespionage campaign backed by a foreign government against a national aerospace industry. Discuss similarities and differences of the threat structure across the following dimensions: typical group size and organization, funding amount and sources, available intelligence sources, TTPs, target(s), and motivation.


## Further Reading

* Juan Tapiador. [A book list on the computer underground culture](https://0xjet.github.io/3OHA/2021/03/24/post.html). 24 March 2021.
* K. Thomas, et al. [SoK: Hate, Harassment, and the Changing Landscape of Online Abuse](https://www.computer.org/csdl/proceedings-article/sp/2021/893400a473/1oak94nz0AM). 2021 IEEE Symposium on Security and Privacy (SP), pp. 247-267.

