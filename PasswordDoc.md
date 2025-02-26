# Password Documentation
Passwords are a form of authentication that serve as a key to verify the identity of an individual. They are strings of characters that a person must remember and use to gain access to various systems or accounts. A password acts as a secure identifier, ensuring that only the rightful user can access their personal data or services.
Passwords can be used in multiple forms, from websites for users personal accounts, individual applications and services externally outside of the browser. To even users work machines, it being commonly used everywhere where identifiers are put in place.
Despite the growing alternatives in place like biometrics, and one time passwords, passwords are still widely used within all services. This is due to multiple reasons.
- **Simple implementation** for developers
- **Minimal development knowledge** required to integreat passwords
- **Wide support** across services and applications with tools built in and avaliable on all services
- **Universal applicability**, working across a vast amount of applications types, without causing compatability issues or dependancies needed for other applications

![Authentication Factors Diagram](https://images.ctfassets.net/xqb1f63q68s1/6zYhZbrGuVkpM6oobfPeUB/40ed75192d4f99ce898a2ec85e793af3/Authentication_Factors.png)

https://www.descope.com/learn/post/authentication-types

With this in mind passwords are likely going to remain a key security tool for a large amount of time. However this is only based on the user's behaviour and attitude to passwords. Therefore its essential as a security measure, and important for a user to understand keep secure password hygiene.

This report will go over:
- What makes an insecure password
- The importance of a strong password discussing the consequences 
- How to then make a strong password 
- Examples of a strong password

## What makes a password insecure
Passwords come in multiple forms and sizes. This being an identifier and authentication type to prove that the individual are entering, proving who they are. This being stated to be based on the user. Nonetheless it won't matter if the password is insecure. 

### Insecurity
**Insecurity** in the context of a password, means that identifier is easy to guess, crack or compromise in some other way by an unauthorised actors. An insecure password fails to provide adequate protection against common attacking methods. 
These being brute forcing, dictionary attacks or social engineering. 
The key factors contributing to an individuals password being insecure include: 

### **Short Length**
Less characters in a password leads to easier guessing and cracking of passwords. If a password is shorter there are less combinations therefore meaning it can be cracked quicker. In combination to the increase in computing power meaning more guesses can be made, means passwords can be guessed quicker. 
Imagine a password being 3 characters long. 
If a password can have lower/upper case, digits and special characters menaing there can be 94 possible characters.
There can only be 830,584 (94^3). Which for a computer is very little time for how many possible combinations it sounds. 

### **Common/Predictable Passwords**
Using predictable passwords like, `password`, `qwerty`, `letmein` and others makes it easier for attackers to gain access. Due to the laziness of individuals or overall annoyance due to multiple reasons. These passwords can be brute-forced or dictionary attacks.
Surprisingly `password` is still a very common password, due to password rules not being implemented on website or by organisations. Therefore making it a first guess for individuals.

### **Personal Information**
Easily guessable personal details (birthdays, username, pet names) make it easier for an individual to guess your password. If this information is easily accessible online due to you actively putting it up (social media) it makes to easier for malicious actors to gain this information making guesses. 
As well as other tools having information to scrape and collect the information automatically making it easier to guess.
If your birthday includes is something like a pet named `Emily` using a password like `Emily1234` could be used or `PetEmily1234` is an insecure choice as this can be guessed by malicious actors.  

### **Lack of Complexity**
If a password is too simple, i.e. not including special characters, digits, and upper and lower case, this makes it easier for automated tools to guess. This is due to having less combinations which can be guessed for a password. Meaning it will take less time to process out a response of guesses. The same applies if its known guessable words, as they maybe at the top of dictionary attacks or included in those lists as they are a combination of words people use.

![Diagram showing what makes weak and strong passwords](https://www.keepersecurity.com/blog/wp-content/uploads/2023/07/Tips-and-Rules-for-a-Strong-Password.png)

https://www.keepersecurity.com/blog/2023/07/18/top-five-password-security-tips/

Say if an individual had a password only made up of upper case characters at a length of 8 digits, this would only mean 26 combinations of characters for 6 characters. Meaning a guess of only 308915776 (26^6) combinations which won't take a machine long to automate and go through that process. 
However if an individual has a special character, a digit and lower/upper case within the password, it means 94 possible combinations are avaliable for a single word, taking 308915776 (26^6) to 689869781056 (94^6) which is less feasable for a computer to guess.

### **Reused Passwords**
It's also important to not reuse passwords. Your password may already be avaliable on a website that has already been compromised originally. Therefore meaning it is in a wordlist a malicious individual can use to brute force other websites and accounts. Meaning your other logins can also be compromised due to using the same password. 
To check what accounts your details have been compromised on you can look at https://haveibeenpwned.com/ 
This checking if the individual breaches have effected your account and take action accordingly.

### **Lack of Two-Factor Authentication**
While not inherit to passwords directly, this is an important mention. As it allows for more layers of protection if your password is compromised, due to an authenticator being provided. Compensating for weak passowrds as well as giving more awareness for when your password has been compromised, reacting to protect your account further. 

## Importance of a strong password
Passwords are the first line of defense against our confidential and private information on most systems. Therefore it is important to make sure we can stop it from being breached by malicious actors easily, and protect your personal information on systems and services.
Passwords are actively being used on your: 
- **Bank accounts**
- **Other financial accounts**
- **Email**
- **Social Media**
- **Work or school machines**

As listed some of these accounts contain pivotal personal information like financial details, private conversations and persoanl details. So making sure we have access to our own private information is important, therefore setting up a strong password. Being hard to crack, also reduces the chance of identity theft and online privacy of data we contain.

## Consequences of a weak password
However if you don't have a strong password, this can then be compromised by malicious individuals. These individuals may do different actions with the information gained from accessing your confidential information. With the consequences of having a weak password including:

### **Account Hacking**
If using a weak password a malicious actor can easily guess this. Once gaining access they can do different actions:
- Steal personal information, name, address, credit card information
- Take control of your accounts like email or social media, causing potentional reputational damage.
- Use the account for phising or sending spam to contact
- Take control of a work machine to access more company information

### **Identity Theft**
Weak passwords increase the chance of impersonations, using personal details you would know to open accounts in your name, commit fraud or apply for local loans just by having your personal information.

### **Financial Loss**
If a weak password protects your bank account, an individual can take `access` of your bank account. Making online purchases, payment apps, or send to other individuals making unauthorised transactions on the account. Another type is ransomware attacks, which would lead to more financial loss.

![Image showing how weak passwords can lead to ransomware attacks, and financial loss](https://www.keepersecurity.com/blog/wp-content/uploads/2024/02/How-a-weak-password-can-lead-to-a-ransomware-attack-1.png)
https://www.keepersecurity.com/blog/2024/02/29/how-weak-passwords-lead-to-ransomware-attacks/

### **Damage of Reputation**
A weak password could be used on a social media account or work account. If this gets breached the malicious actor may post inapproriate content, spread misinformation or access private conversations on the account. This can harm your relationship to other individuals or workplaces.

### **Compromising other accounts**
If a weak password is reused on other platforms, other accounts can be compromised as well. Leading to multiple accounts you own being compromised and used for malicious activities.

### **Details and Account Loss**
If an individual has access to an account. They can request to change the password to an unknown password, making it harder to regain control of your accounts, possibly being lost for good. This is the same if the same password is reused on other accounts, as they may also be lost in the process.

## How to make a strong password 
Shown previously there is a large amount of consequences for not developing a strong password. Ranging from annoying to compromising a users personal information, compromising you and a possible organisation you may work for. Therefore we need to discuss how to make a strong password, using these as a general rule:

### **Length**
It's important to have a password longer than 8 characters, preferably 15 characters, being harder to brute force the password guess.

### **Mix of Characters** 
It's to have at least a mix of characters including at least one of:
- Uppercase letters (A-Z)
- Lowercase letters (a-z)
- Numbers (0-9)
- Special characters (e.g., !, @, #, $, %, &, *)
Giving more possible choices the character could be and making it harder to guess an individuals password

### **Common phrases**
Avoid common phrases for passwords like `123456` or `password` as they can be easily guessed and are known wordlists, being the first things tried.

### **Don't Reuse Passwords**
Best practice is to not reuse passwords on multiple sites and services. If one gets compromised, your other accounts and services will also be compromised

### **Mnemonic passwords**
An alternative to making a password is mnemonic passwords, taking a sentence and taking the first letter of the word and mixing other combination of characters to read. 
An example being `I Love Password Making A Lot Too` 
Then turning into `ilpmalt`, include more combinations and add characters to pad out the password to get `Il1Pm@1t0o` to make a strong password as an alternative to make it memorable.
To look at more information about mnemonics you can view information here: https://proton.me/blog/create-remember-strong-passwords

### **Alternative Tools**
Alterantive tools can be used to produce a strong password, consider using:
- **Multi-Factor Authentication** as it can allow for you to be alerted if your password is compromised and as another layer as security
- **Password Managers** can be a tool for consideration, as you can generate complex passwords for all accounts. Securely storing your passwords in place, however it is questionable depending on the software used.

![Diagram showing how Password managers work with passwords](https://delinea.com/hs-fs/hubfs/delinea-how-does-a-password-manager-work-blog.png?width=750&name=delinea-how-does-a-password-manager-work-blog.png)

https://delinea.com/blog/beyond-password-managers-to-pam-solutions

## Examples
Heres a small list of contained passwords randomly generated being very secure:
- S5f5.6|h.n'C`e?
- l>E24751}M~ptY}
- lE395s[-a{o4/@a
- bU95C=5Snff?/C0
- X7q9/4=e4uNyyHV
- Zk184<6i;4|iU!h
- 941l@)Am:r@_&3f

Another tool for further generation maybe https://www.lastpass.com/features/password-generator
