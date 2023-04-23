1. Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a financial services company that provides a wide range of services to their clients. Due to the nature of a financial institution, every little bit of data that is sent back and forth from their servers is highly sensitive information. It's very important that this information is protected from attackers because any breach at all could involve the loss of real money for any or all of Artemis's clients. Any breach isn't only an immediate loss of money, but also a loss of trust, and without trust it's nearly impossible to gain new customers and difficult to maintain the current ones. For these reasons, Artemis wanted to modernize their their codebase and bring it up to date with the most modern and cutting edge methods of application security.

2. What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I enjoyed implementing input validation where it was lacking. It's such a simple yet such an important aspect of application security. All user input into the application is considered untrusted data so it's of great importance to keep strict guidelines on what data can be accepted into the application and blocking out anything that is not whitelisted. Once we have that data, it's important to sanitize it to prevent against injection attacks. Adding this security is of high value to any company's wellbeing because if the code is written well and secure from the start, they can spare themselves of so much headache and money later down the road. It's better to prevent attacks from the start than to react to them once they happen.

3. What part of the vulnerability assessment was challenging or helpful to you?

At first, running the static test is a bit tough to configure and then once it's run, there is a ton of information and is a bit of an overload the first few times one runs and looks at the report. I did find it extremely helpful that OWASP provides a link to a detailed description of each vulnerability in the report. It helped me learn a lot about what, in general, these vulnerabilities entail and they provide useful guidelines on how to mitigate these vulnerabilities.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

First and foremost, the layers of security were increased by simply updating the libraries to their most current version. For many vulnerabilities, the recommended solutions on the OWASP website is to just update to the most current version. Such a simple thing can help mitigate a lot. Also as I stated above, input validation and sanitization of the input did most of the heavy lifting and is an extremely strong layer of defense if secure coding is used. In the future, I would make sure that whitelisting is used whenever possible rather than blacklisting because the administrators of the application should get to control exactly what the user is able to do. Aside from that, I would follow the best recommendations from the OWASP website for each individual vulnerability.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To make sure it's functional, I would simply run it and if there are no compiler or logic errors then the next step of making sure it's secure would happen. Using a SecDevOps framework of development, the code written should already be secure as security should be an integral part of the development process itself. After making sure my coding looks secure, I'd run the vulnerability report and check fof vulnerabilities. After taking care of those, I'd run it one more time to ensure that none of the changes I made introduced any additional vulnerabilities.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

My favorite resource was the OWASP website. I particularly like it because it's open source and volunteer run. There isn't really any money involved and it's just a group of people, "good guys" basically, who do this for the main purpose of helping others protect their applications and websites against nefarious actors. In the future I can always use it as a resource to ensure I'm taking the right steps in developing a secure application with secure code.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

From this specific assignment that I uploaded, I would show them the mitigation plan because it shows that I have knowledge of how to use the tools including the vulnerability report and shows my knowledge of several different methods to thwart attackers and to create an application that's secure.
