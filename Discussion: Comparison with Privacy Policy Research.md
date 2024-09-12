We recognize the importance of privacy policy research in conveying information to users and acknowledge the similarities with Web3 auditing, particularly in terms of how complex terminology impacts user comprehension. However, due to the fundamental differences in the ecosystems where these two operate, our findings on Web3 auditing can provide novel insights for the secure development of the Web3 ecosystem. 
Therefore, in this section, we first compare the key differences between privacy policies and Web3 auditing that lead to distinct user perceptions and design implications. We then explore the similarities, highlighting how Web3 auditing can benefit from insights gained in privacy policy research.

## Differences Between Privacy Policies and Web3 Auditing

While privacy policy research offers valuable insights, there are significant differences between privacy policies and Web3 auditing. These differences highlight the unique challenges and considerations specific to Web3 auditing, underscoring the need for tailored research in this area.

### Differences in Information Delivery
Privacy policies are mandatory agreements that users must accept before using most applications, often without needing to actively retrieve them [1]. In contrast, Web3 audit results are supplementary security information that users do not directly encounter in the application interface. Therefore, for Web3 auditing, it is important to consider whether audit information is easily accessible to users (Section IV). However, as we found that users generally reported easy access to audit information, no additional design recommendations were made in this regard.

### Differences in User Decision-Making
Privacy policy research focuses on users granting permission for applications to access their personal data [2], with prior studies highlighting how privacy policies influence users’ data management behaviour. These studies also reveal the existence of the “privacy paradox,” where users value privacy but rarely read policies or seek more information [3]. Web3 audits, however, primarily affect users’ evaluations of whether to engage with Web3 applications. As such, the focus here is on how audit information influences users’ decision-making (Section VI). These two areas differ significantly in how they impact users, leading to distinct design implications for information transparency. While privacy policy research emphasizes transparency in data collection [4], Web3 auditing focuses on the transparency of the auditing process.

### Differences in Application Information Disclosure Motivation
Privacy policy disclosure is legally required, meaning applications are often passive in providing this information and may obfuscate unethical data handling practices [5]. In contrast, Web3 audits are voluntary security verification measures aimed at building trust through third-party certification, with additional costs paid to external security firms. Therefore, when proposing design implications, privacy studies focus on preventing users from overlooking potential privacy violations, using solutions like optimizing informed consent methods [4], [6]. In contrast, Web3 auditing research emphasizes whether users recognize the security practices of applications (Section V) and how to design audit information to enhance user trust.

### Differences in Educational Role
Security awareness related to privacy in Web2 is often enforced by government regulations and integrated into school curricula, ensuring users receive basic knowledge through mandatory mechanisms [7]. In the decentralized Web3 ecosystem, there is no centralized authority responsible for security education. Therefore, design implications for security awareness target different entities. While privacy policy research focuses on professional groups like students or employees with similar knowledge backgrounds and skill levels [8], Web3 auditing targets end users in a more complex environment. Our research found that Web3 audit firms and decentralized organizations play a crucial role in educating users about security (Section V-A3), offering valuable insights into general security education, as covered in our design implications (Section VII-C1).

## Similarities between Privacy Policy Research and Web3 Auditing Research

Though privacy policy research and Web3 auditing address different domains, they share several user challenges that Web3 auditing can learn from. These similarities provide opportunities for Web3 auditing to adopt proven strategies from privacy policy studies to improve user comprehension and trust.

### Similarities in User Challenges with Technical Complexity
Both privacy policies and Web3 audit reports contain technical language that can overwhelm users, making it difficult to fully understand the content [1]. Research in privacy policy studies shows that simplifying language or using visual aids, such as icons, can improve user comprehension [9]. Similarly, Web3 auditing could benefit from adopting these strategies by presenting audit results in a more accessible format.

In fact, some of these practices have already been adopted by Web3 auditing, such as using absolute security scores. However, this introduces a new challenge, as we found that users struggle to understand the relationship between the score and actual security (Section IV-C).

### Similarities in Lack of Standardization and Consistency
Both privacy policies and Web3 audits face challenges due to the lack of standardization in how information is presented. In the case of privacy policies, this lack of consistency across platforms makes it difficult for users to compare and understand the privacy practices of different services [4]. This is similarly reflected in Web3 auditing, where audit reports can vary significantly depending on the auditing firm, making it hard for users to consistently evaluate security practices across different decentralized applications (Section IV). Drawing from privacy policy research, Web3 auditing practices could benefit from developing standardized formats and criteria (Section VII-C2), helping users better navigate and compare audit results across various platforms.

### Similarities in User Skepticism Towards Effectiveness
User scepticism about the effectiveness of privacy policies has been well-documented, with users often feeling that privacy policies provide little real protection and serve more as a formality [10]. Similarly, Web3 users may question the value of audit reports, often due to distrust in audit firms and a lack of understanding of the audit information (Section V).

To address this scepticism, privacy research has recommended greater transparency and user-centred communication to improve trust [10]. Web3 auditing could adopt similar approaches by making audit processes more transparent and involving users in the auditing ecosystem, such as providing clear and detailed explanations of how audits are conducted and the security guarantees they offer (Section VII-C2).

---

## References

1. S. Bugiel, S. Heuser, and A.-R. Sadeghi, “Flexible and fine-grained mandatory access control on android for diverse security and privacy policies,” in 22nd USENIX Security Symposium (USENIX Security 13), 2013, pp. 131–146.
2. Y. Chang, S. F. Wong, C. F. Libaque-Saenz, and H. Lee, “The role of privacy policy on consumers’ perceived privacy,” Government Information Quarterly, vol. 35, no. 3, pp. 445–459, 2018.
3. S. Kokolakis, “Privacy attitudes and privacy behaviour: A review of current research on the privacy paradox phenomenon,” Computers & security, vol. 64, pp. 122–134, 2017.
4. B. Custers, S. van der Hof, and B. Schermer, “Privacy expectations of social media users: The role of informed consent in privacy policies,” Policy & Internet, vol. 6, no. 3, pp. 268–295, 2014.
5. I. Pollach, “A typology of communicative strategies in online privacy policies: Ethics, power and informed consent,” Journal of Business Ethics, vol. 62, pp. 221–235, 2005.
6. M. Pascalev, “Privacy exchanges: restoring consent in privacy self-management,” Ethics and Information Technology, vol. 19, no. 1, pp. 39–48, 2017.
7. A. Soumelidou and A. Tsohou, “Towards the creation of a profile of the information privacy aware user through a systematic literature review of information privacy awareness,” Telematics and Informatics, vol. 61, p. 101592, 2021.
8. V. Švábenský, J. Vykopal, and P. Čeleda, “What are cybersecurity education papers about? a systematic literature review of sigcse and iticse conferences,” in Proceedings of the 51st ACM technical symposium on computer science education, 2020, pp. 2–8.
9. A. Öksüz, S. K. Obaidat, and G. S. Sohal, “Simplifying the language in privacy policies: The role of icons,” IEEE Access, vol. 5, pp. 15045–15059, 2018.
10. A. Zwitter, “Skepticism in privacy policies: The ongoing challenge,” Computers & Security, vol. 69, pp. 84–92, 2018.
