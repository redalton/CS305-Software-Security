# CS305-Software-Security

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company focused on delivering financial plans to their clients. Artemis financial is looking to update their website to include 
additional security features such as a checksum validation and encrpyted communication to protect their customers.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
One thing I was able to do very well was identifying the legitimate vulnerabilities from the false positives. I reviewed the CVEs to see if the vulnerability is relevant
to the code and how its being used. It is important to bake security practices into your coding practices as attackers are constantly looking for insecure code and
vulnerabilities. Security incidents can compromise customer data and cost a company trust of their users. Sometimes they can never get this back. Thats why every 
developer should be incorporating security practices to their development.

What part of the vulnerability assessment was challenging or helpful to you?
The vulnerability assessment process chart was very helpful to me. Breaking down the principles of security into the relevant areas in the process chart helped me 
break down those concepts in my own code to make sure I'm covering all my bases.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased layers of security by combining multiple methods of security testing. I used static testing using Maven to scan my code dependencies for vulnerabilities. 
I also utilized code review to identify logical, design, and exception handling errors. In the future, I would design the security tests based on the criticality and 
nature of the program being developed. I would definitely use maven in the future to perform static dependency checks.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I reviewed my code to make sure it was free of errors and did not introduce insecure practices. After refactoring, I ran a maven dependency check on my code to see if I
introduced any new vulnerabilities. I compared the check against my previous runs and saw that no new vulnerabilities were added.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The use of Maven for dependency checking is a best practice that I can see myself using in future development. Searching for the most up-to-date government regulations
on security and privacy is another practice that I plan to use to ensure my code is secure.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show my ability to critically assess and use great judgement in verifying vulnerabilities using Maven dependency checks and code reviews. The critical 
assessment skills I used in this project can adapt and be utilized in any future code vulnerability assessments. 
