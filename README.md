# CS-305-Software-Security

**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**

Artemis Financial was a financial consulting company that wanted to modernize its software and improve the security of its web application. The company needed secure communication for its RESTful web application because it handled sensitive financial information. The main issue Artemis Financial wanted addressed was the risk of software vulnerabilities and insecure communication. My job was to review the application, identify security weaknesses, and refactor the code so that the application used stronger security practices.

**What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**

One thing I think I did well was using a structured approach to find and document the software security vulnerabilities. I reviewed the code manually, looked at dependency issues, and used OWASP Dependency-Check to identify known vulnerabilities in third-party libraries. I also tried to explain why the vulnerabilities mattered instead of just listing them. Secure coding is important because even one weakness can create a risk for the company and its clients. Software security adds value because it helps protect customer data, lowers the chance of a breach, builds trust, and helps the company avoid financial or legal problems.

**Which part of the vulnerability assessment was challenging or helpful to you?**

The most challenging part of the vulnerability assessment was working through the dependency check results. There were a lot of vulnerabilities listed, and it took some effort to understand which ones were actual concerns and which ones might be false positives. Even though it was challenging, it was also helpful because it showed me how many security risks can come from outdated or vulnerable dependencies, not just from the code I write myself.

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

I increased layers of security by adding HTTPS with a self-signed certificate, using a secure hash algorithm, and reviewing the dependency check results. These steps helped protect communication, verify data integrity, and identify vulnerable components. In the future, I would use tools like OWASP Dependency-Check, manual code review, secure coding standards, and current vulnerability databases to assess risk. I would also look at the type of data being protected, the severity of each vulnerability, and how likely it would be for that weakness to be exploited before deciding on mitigation techniques.

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

I made certain the code and application were functional and secure by running the application, testing the secure HTTPS connection, and verifying that the checksum endpoint worked correctly. After refactoring the code, I ran another dependency check to make sure I had not introduced new vulnerabilities. I also compared the results and reviewed the application behavior to make sure the security changes did not break the basic functionality.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

Some resources, tools, and coding practices that I found helpful were OWASP Dependency-Check, Java Keytool, Java’s MessageDigest class, Maven, Eclipse, and the secure coding concepts from the course. I also found it helpful to add comments in the code and document what I changed. Good practices like using current dependencies, validating inputs, using secure algorithms, and testing after making changes are things I can use again in future assignments or work tasks.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

For future employers, I could show the vulnerability assessment report, the refactored code, screenshots showing HTTPS working, the checksum implementation, and the before-and-after dependency check reports. These examples would show that I can review an application for security issues, apply secure coding practices, use security tools, document my findings, and verify that the software still works after security improvements are made.
