# PASSWORD STRENGTH CHECKER #
This project aims to enhance digital security by assessing the robustness of user-generated passwords. This software tool evaluates passwords based on various criteria, including length,and complexity. Users input their chosen passwords, and the tool provides a strength rating along with personalized recommendations for improvement. By encouraging stronger password choices and educating users about cybersecurity best practices, this project contributes to the overall protection of sensitive information and mitigates the risk of unauthorized access to online accounts.  It promotes the importance of secure passwords and empowers individuals to take control of their online security.

## Requirements ##
### Requirement Analysis ###

* User Interface Requirements
  * a simple and intuitive command-line interface (CLI) or graphical user interface (GUI) for users to input and check passwords.
* Functional Requirements
  * assesses the strength of passwords based on various criteria, including length and character diversity.
  *	provides a categorization indicating the strength level, such as weak, moderate, or strong.
  *	allows users to check multiple passwords in a single session.
  *	offers password suggestions and tips for strengthening weak passwords.
* Security Requirements
  *	passwords inputted by users are securely handled, with no storage or logging of the passwords.
  *	doesn’t pose any security risks or vulnerabilities to users' passwords.

### Hardware Requirement ###

* Softwares
  * Python (I used version 3.12.2)
  * IDE for writing and running the code
* Processor (CPU)
  *	A standard modern processor like Intel Core i3 or equivalent.
  *	Even lower-tier processors or older generations can handle the computational needs of a password strength checker.
* Memory (RAM)
  *	A minimum of 2GB RAM is sufficient for running the password strength checker.
* Storage
  *	Minimal storage space is required for the application itself, usually a few megabytes.
* Operating System
  *	The password strength checker written in Python can run on various operating systems, including Windows, macOS, Linux, etc.

### Criteria for assessing password strength ###

A password is said to be strong if it satisfies the following criteria: 
  * It contains at least one lowercase English character.
  * It contains at least one uppercase English character.
  * It contains at least one special character. The special characters are: !@#$%^&*()-+
  * Its length is at least 8.
  * It contains at least one digit.
A strong password is one that satisfies all above conditions. A moderate password is one that satisfies first three conditions and has length at least 6. Otherwise password is week.

### Sample demonstration ###

https://github.com/Shristi-17/password-strength-checker/assets/77795561/22176d60-157d-4b1e-8804-81a84cd0f375
#### This video gives a demonstration on how the program responds for the different types of inputs i.e, passwords. I used them as a sample it works for any other password also. ####

I hope it helped ✌️✌️✌️
