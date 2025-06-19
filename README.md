In Cyber Security, our jobs involve protecting organizations from a wide range of
threats, with phishing being one of the most common and dangerous. We work to
detect, prevent, and respond to phishing attacks that attempt to trick users into
revealing sensitive information or downloading malicious software. This includes
monitoring email traffic, training employees to recognize suspicious messages, and
implementing technical controls like email filters and multi-factor authentication. By
staying ahead of phishing tactics and educating others, we help minimize the risk of
data breaches and maintain the security and integrity of our systems.
For our project, we will demonstrate how phishing attacks are executed to raise
awareness about the tactics cybercriminals use to obtain sensitive information and how
that data may be exploited. Phishing continues to be one of the most prevalent and
successful attack vectors used to compromise personal, financial, and organizational
systems. These attacks often succeed due to a lack of user awareness and insufficient
cybersecurity training. Through this project, we aim to present real-world phishing
scenarios and explain the social engineering techniques commonly employed by threat
actors. Our objective is to educate users on how to recognize, prevent, and report
phishing attempts, thereby contributing to a more security-aware environment and
reducing the overall risk of compromise.
The first step we took was downloading a tool on Kali Linux called the Social-Engineer
Toolkit (SET). This powerful framework is widely used for simulating real-world social
engineering attacks, including phishing, credential harvesting, and website cloning.
For our demonstration, we chose to focus on website cloning. Using SET, we cloned the
LinkedIn login page to create a convincing replica. By using DNS spoofing (also known
as DNS poisoning), we were able to redirect a victim’s request for github.com to our
local machine's IP address. As a result, when the target visited what appeared to be the
legitimate Github’s site, they were actually interacting with our cloned version. Any
credentials or sensitive information entered into the fake page were captured and sent
directly to us.
Next, we created a phishing email to accompany our cloned website and DNS spoofing
setup. With everything in place, we crafted a fake email containing a link that appeared
to direct the recipient to Github. This tactic is often used in whale phishing. A targeted
phishing attack aimed at high-profile individuals within an organization, such as CEOs
or executives.
In our example, we sent the email to a fictional executive named John Doe. When John
opened the email, clicked the malicious link, and entered his credentials into the fake
LinkedIn login page, those details were captured by our system. With this stolen
information, an attacker could attempt to access not only the victim’s LinkedIn account
but also their email, social media, bank accounts, and more.
Many users reuse the same password across multiple platforms, so a single successful
phishing attack can quickly escalate into a full-blown security breach, financial loss, or
even identity theft.
Phishing remains one of the most significant cybersecurity threats due to its
effectiveness in exploiting human trust and behavior. Through our project, we
demonstrated how attackers use tools like the Social-Engineer Toolkit to clone
legitimate websites and combine them with DNS spoofing and targeted phishing emails
to harvest sensitive information. This highlights the critical importance of user
awareness, robust technical defenses, and ongoing cybersecurity training. By
understanding these attack methods, individuals and organizations can better
recognize, prevent, and respond to phishing attempts—ultimately strengthening their
overall security posture.
