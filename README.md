# The Science of Stolen Data
&nbsp;By Emma Adelmann<br>

## Introduction

* **Problem**: The prevalence of large-scale data breaches and their far-reaching effects
* **Background**: <br>
&emsp;&emsp;
A *data breach* is the exposure of data to parties who are not authorized to access it. A data breach can be caused by digital vulnerabilities, but may also be caused by the direct actions of humans (for example, theft or human error). Culprits include "accidental insiders" -- those who may stumble across confidential data without having the proper permissions to view it. Even an accidental viewing of the secret data is considered a breach. In some cases, a device containing the data may be lost or stolen. There are also malicious insiders and outsiders who aim to access confidential data, possibly using it to harm a company and its customers [4]. For the average user, credentials and personal information may be made available to the public, leaving them vulnerable to hackers. Depending on nature of the information that was leaked, the user could fall victim to identity fraud. If passwords were leaked (and if a user is among the 65% who reuse their passwords across websites and services), cybercriminals could compromise other accounts across the internet without having to use any sophisticated methods [3].<br>
&emsp;&emsp;
In the United States, if a data breach of an entity exposes any personally identifiable information belonging to users, then the entity is required by law -- depending on the state -- to disclose the breach and notify the affected users [6]. After the breach, the victim can do little to take back the information that has been leaked. However, they may harden their security to make such an attack less likely in the future.
* **Questions**:
    - Who/what is the primary culprit behind data breaches?
    - When it comes to data security (weighing both the frequency and magnitude of incidents), should an organization bolster their physical security in order to protect digital assets?
    - Is there a geographic pattern to these data breaches? If so, where do they take place most often?
    - Does a breach typically take place over a long or short period of time? During what year did the most data breaches take place?
    - Have threat trends (i.e the type of breach) evolved over the years?
* **Justification**: <br>
&emsp;&emsp;
In 2019, the average cost of cleaning up a data breach was over 8 million dollars -- with the healthcare industry being hit the hardest [5]. When we consider the sometimes priceless nature of data, we can understand that a data breach is clearly something that governments, organizations, and end users would wish to prevent. However, in order to do so, we must find out who or what is resposible for the majority of breaches. Once we have this information, we can harden our systems and introduce new security policies to lower the likelihood of a breach.<br>
&emsp;&emsp;
It is becoming increasingly clear that physical security is innately intwined with cybersecurity. The US Cybersecurity & Infrastructure Security Agency recommends the use of a "holistic" approach to physical security and cybersecurity, as opposed to a "siloed" approach in which they are treated as two separate responsibilities (leading to less coordination within the organization and more attacks) [2]. This is particularly relevant to IoT and IIoT systems, but does it also apply to data security?<br>
&emsp;&emsp;
According to IBM, it takes 280 days on average to both detect and respond to a data breach [1]. This could mean that the organization simply took a long time to find evidence of the incident, or the attacker (if any) could have had constant access to the breached information for a period of time. This extended breach could spell trouble for both the targeted organization and its users.
* **Datasets**: https://www.kaggle.com/alukosayoenoch/cyber-security-breaches-data
* **Explanation of the Data**: This dataset describes over 1000 data breaches taking place from 1997 to 2014. It includes information on the location of the breached info, affected parties, type of breach, and when it took place. 
* **Ethical Concerns/Considerations**:
    - As defenders gain more information about the state of cybersecurity, so too do attackers. However, the information must remain accessible to increase the chances of more "good guys" and good-guys-in-training coming across it.
    - In many cases, data from a breach is leaked on the internet. Services like https://haveibeenpwned.com exist to search for compromised emails and passwords. You can also find dumps of leaked information through a simple Google search. No sensitive data is included in this dataset -- it is theoretically possible to look up the incident using the provided details and then trying to locate the leaked data, but I do not see this being a significant issue. There is usually no real need for a hacker to look up a specific incident, and it is public information anyway.
    - Organizations named in this dataset may experience damage to their reputations. This is unavoidable since they had to make their incident public in the first place. Analyzing such data allows us to better understand how and why data breaches occur, helping to prevent them from happening in the future.<br><br>

**Sources**:<br>
[1] “Cost of a Data Breach Study,” IBM, 2020. [Online]. Available: https://www.ibm.com/security/data-breach. [Accessed: 30-Apr-2021]. <br>
[2] “Cybersecurity and Physical Security Convergence,” Cybersecurity & Infrastructure Security Agency. [Online]. Available: https://www.cisa.gov/sites/default/files/publications/Cybersecurity%20and%20Physical%20Security%20Convergence_508_01.05.2021.pdf. [Accessed: 30-Apr-2021]. <br>
[3] K. Bowen, “Your Employees Are Reusing Passwords – Find Out How Many,” Infosecurity Magazine, 30-Jun-2020. [Online]. Available: https://www.infosecurity-magazine.com/blogs/your-employees-reusing-passwords/. [Accessed: 24-May-2021].<br>
[4] Kaspersky, “How Data Breaches Happen,” www.kaspersky.com, 26-Apr-2021. [Online]. Available: https://www.kaspersky.com/resource-center/definitions/data-breach. [Accessed: 30-Apr-2021]. <br>
[5] M. Puranik, “What Is The Cost Of A Data Breach?,” Forbes, 02-Dec-2019. [Online]. Available: https://www.forbes.com/sites/forbestechcouncil/2019/12/02/what-is-the-cost-of-a-data-breach/. [Accessed: 30-Apr-2021]. <br>
[6] P. Greenberg, “Security Breach Notification Laws,” National Conference of State Legislatures, 15-Apr-2021. [Online]. Available: https://www.ncsl.org/research/telecommunications-and-information-technology/security-breach-notification-laws.aspx. [Accessed: 30-Apr-2021]. <br>
