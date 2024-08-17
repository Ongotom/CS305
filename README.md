# CS305
SNHU CS 305

•	Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
The client is a financial firm that curtails individualized  financial plans for each client. AF approached us to modernize and secure their software to preserve customer data and be governmentally compliant.

•	What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
The thing I did well was recognizing out of date dependencies. It should be the first thing any entity checks when modernization is an ask. This client cannot stay in business unless they are completely secure. There is no over estimation of the value of security to a financial business.

•	Which part of the vulnerability assessment was challenging or helpful to you?
The difficult parts was manually assessing the code quality. Trying to understand the implications of input validation, protecting from SQL injection and how public classes could be harmful in a program.

•	How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
The main increase to security was introducing the industry standard SHA-256 algorithm cipher. There are not many more secure ciphers as this exponentially reduces the chance of collsions, so brute force attacks either can’t work or would take centuries. 

•	How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I used static testing that Maven has available. It’s a simple plugin and is not time consuming. It gives a great overhead view of dependency issue in your code and allows for suppression of known issues that don’t concern your project. 

•	What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Being able to work with hashes felt very valuable, as well as generating my own certificates incase I want to do a local server for increased security.
•	Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
The ability to implement real world ciphers and checksums to secure data is a great asset and a fundamental skill if I ever want to pursue a career in cybersecurity. Being able to properly keep software up to date and manually checking code for input validation would get me in the door.
