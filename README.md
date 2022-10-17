# CS-305-T1166 22EW1
## Ryan Betts

#### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a finance consulting firm that manages financial plans for retirement, savings, or insurance purposes. Artemis Financial stores sensitive data such as personal customer data and financial transactions which they would like to ensure is secure.
#### What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I think I did very well in analyzing the company’s security requirements based on the type of company they are and the regulatory requirements a financing company has in order to safeguard their customer’s data. It is important to code securely to ensure that the software you have developed is not exploited by criminals that could cause sensitive data to be exposed, data to be lost, or systems to become disabled. Software security adds value to a company’s overall wellbeing because customers can trust a company that secures its data and has reliable products.
#### What part of the vulnerability assessment was challenging or helpful to you?
The most helpful part of the vulnerability assessment was running the dependency check tool to automatically check all dependencies for known vulnerabilities. This allowed me to update those dependencies and reduce the threats against the application.
#### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased security in this codebase by implementing encryption on a static data string to generate a checksum. This checksum can be used to ensure that the data has not been modified. I will also use the dependency check tool to ensure dependencies do not have vulnerabilities and update those that do. I will also always use HTTPS on web applications. HTTPS ensures that communication between the server and client is secure and cannot be modified or monitored by third parties.
#### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
By performing vulnerability assessment scans after refactoring code, I can ensure that my code did not introduce any new vulnerabilities. I also perform functional testing on my code by running the code and ensuring that there are no errors.
#### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The OWASP Dependency Check Maven plugin can be useful in the future to check for vulnerabilities within a project’s codebase and its dependencies. https://jeremylong.github.io/DependencyCheck/dependency-check-maven/index.html
The Oracle Key and Certificate Management tool can be useful to create self-signed certificates for implementing HTTPS on internally developed web applications.
https://docs.oracle.com/javase/6/docs/technotes/tools/windows/keytool.html
#### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
Employers may want to ask what kind of things I do to ensure that the code I write is secure. I would show how I used HTTPS to ensure that communication between a client and server is secure. I would also show the employer how I used the dependency check plugin to ensure dependencies are up-to-date with no vulnerabilities.

