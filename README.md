# HONEYPOT

## Overview

 We will focus on honeypot here.

This Report provides:

* The definition of a honeypot
* How honeypots work
* The complexities of honeypots varies
* Different types of honeypots and how they work
* Benefits of a Honeypot
* The dangers of honeypots



# The Definition of a Honeypot

Honeypot might remind you of Mata Hari style spies, shocking plot twists and intriguing schemes but in the cybersecurity context, it has a whole different meaning.

For the las few years, a more proactive approach to cyber security has been on the rise. Instead of waiting for the next cyber attack to happen, many organizations prefer taking things in hand. They actively look out for the vulnerable spots on the façade of their cyber security organization and carry out pen testing, vulnerability assessment and such procedures. Being one of the rather more banzai strategies of cyber security, honeypot aims to provide an additional layer of security. In this article, we will discuss what honeypot is in detail and how it can be very beneficial for your organization.

In computer terminology, the term honeypot refers to a security structure or mechanism that is built to deflect the attackers. In other words, a honeypot is there to distract the attackers from valuable assets of the organization.

Honeypot can be defined as a system that is attached to the network. It is set up to be a decoy. It lures the hackers and wastes their time as they try to gain unauthorized access to the network or systems of the organization.

Although honeypots have gained a significant interaction in the last few years, it must be noted that they have been around for quite some time. In fact, honeypots can be considered as one of the oldest security measures in the cyber security discipline.





# The Complexities of Honeypots Varies

There are different types of honeypots, each designed for different production or research purposes.

### Pure Honeypot
A pure honeypot refers to a full-scale system running on various servers. It completely mimics the production system. Within a pure honeypot is data made to look confidential, as well as “sensitive” user information, which have a number of sensors used to track and observe attacker activity.

### High-interaction Honeypot
A high-interaction honeypot is designed to get attackers to invest as much time as possible inside the honeypot. This gives the security team more opportunities to observe the targets and intentions of the attacker and more chances to discover vulnerabilities within the system. 
A high-interaction honeypot may have extra systems, databases, and processes that the attacker will want to try to infiltrate. Researchers can observe how the attacker goes about looking for information, as well as which information they prefer and how they attempt to escalate access privileges.

### Mid-interaction Honeypot
Mid-interaction honeypots imitate elements of the application layer, but they do not have an operating system. Their mission is to confuse an attacker or stall them so the organization has more time to ascertain how to react to the kind of attack in question.

### Low-interaction Honeypot
Low-interaction honeypots are less resource-intensive and gather rudimentary information regarding the kind of threat and where it came from. These are relatively simple to set up, and they make use of Transmission Control Protocol (TCP), Internet Protocol (IP), and network services. However, there is nothing inside the honeypot to hold the attacker’s attention for a considerable amount of time.

# Different Types of Honeypots and How They Work

### Malware Honeypot
Malware honeypots use attack vectors already known to lure in malware. They can, for example, imitate a Universal Serial Bus (USB) storage device. If a computer comes under attack, the honeypot fools the malware into attacking the emulated USB.

### Spam Honeypot
Spam honeypots are designed to attract spammers by using open proxies and mail relays. Spammers perform tests on mail relays by using them to send themselves an email. If they are successful, they can then transmit large amounts of spam. A spam trap can identify a spammer’s test and then block the spam they try to send out.

### Database Honeypot
A database honeypot is used to make decoy databases to attract database-specific attacks like SQL injections, which illicitly manage data. These kinds of honeypots can be implemented using a database firewall.

### Client Honeypot
Client honeypots attempt to lure in malicious servers that attackers use while hacking clients. They pose as a client to observe how an attacker makes modifications to a server during the attack. Client honeypots are typically run in a virtualized environment and have containment protections in place to reduce the risk of exposure to the researchers.

### Honeynet
Honeynets consist of a network of honeypots. With different kinds of honeypots forming a honeynet, several types of attacks can be studied, such as distributed denial-of-service (DDoS) attacks, attacks to a content delivery network (CDN), or a ransomware attack. While a honeynet is used to study different kinds of attacks, it contains all traffic, both inbound and outbound, to protect the rest of the organization’s system.

By monitoring traffic coming into the honeypot system, you can assess:
* where the cybercriminals are coming from
* the level of threat
* what modus operandi they are using
* what data or applications they are interested in
* how well your security measures are working to stop cyberattacks


# Benefits of a Honeypot
Honeypots come with several advantages a security team can leverage to improve network safety.

#### Break Down the Attacker Kill Chain
Attackers move through your environment like predators, scanning your network and looking for vulnerabilities. While they are on the prowl, they may engage with your honeypot. At this point, you can both trap the attacker inside and investigate its behavior. Honeypots also disrupt the kill chain by enticing attackers to invest their time going after the useless information in the honeypot instead of actual, sensitive targets of value.

#### Help in Testing the Incident Response Processes
Honeypots are an efficient way to see how your security team and the system will react to a threat. You can use a honeypot to evaluate the effectiveness of your team’s responses and address any weaknesses in policies.

#### Straightforward and Low Maintenance
Honeypots are both easy-to-implement and effective tools for providing alerts and information regarding the attacker's behavior. Your security team can deploy a honeypot and just wait for an attacker to interact with it. There is no need to constantly monitor the decoy environment, and you do not have to arm it with intel regarding known threats for it to be an effective tool.

