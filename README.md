# cs305
### Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is looking to modernize its web interface, specifically they were looking to implement modern encryption standards and utilize certificates to ensure secure communications.


### What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
It's important to identify and address vulnerabilities found as quickly as possible. I utilized a dependency checker to check for any known vulnerabilities and made adjustments as needed. Software security ensures data protection and compliance which are extremely important in regulated fields such as financials.


### Which part of the vulnerability assessment was challenging or helpful to you?
The OWASP dependency checker was extremely helpful in static testing. Having a database of known vulnerabilites along with what researchers have found about each dependency being used can be a big help in getting a vulnerability report going.


### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
OWASP Dependency was used to check for security issues before even starting the server up. Using SSL for secure communication as well as including a checksum to ensure data integrity. 

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Testing the code after refactoring and re-running the dependency checker.  

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The Oracle documentation was something I had never really looked or needed to use before but I found it to be very useful. So next time I'm contemplating a language for a project I'm honestly more likely to use java than I was 8 weeks ago.


### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show my employer my vunerability reports.
