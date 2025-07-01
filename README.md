# CS-230-Project
Final Project for SNHU's CS-305 Software Security Class
Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

  Artemis Financial was looking to modernize its operations and improve its custom software to ensure it used the most up to date and effective software security practices. They worked with important clientele that required effective security to ensure their financial data was secure. Improving the code and removing inefficiencies without introducing new vulnerabilities as well as reducing the number of any current vulnerabilities found during the process was the main task.
  
What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

  I felt like I did a good job identifiying and making changes to reduce the number of vulnerabilities. The Maven Dependency Check came back with fewer vulnerabilities after my work which gave me validation that I had made some improvements despite being a novice in this field. 
  
Which part of the vulnerability assessment was challenging or helpful to you?

  I found that the most challenging part of the vulnerability assessment was identifying false positives and working to suppress them. The research necessary to identify which vulnerabilities were likely false positives required some legwork.
  
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

  I introduced the SHA-256 hash function to improve security. It is a one-way function, so the hash is irreversible making it imporssible to obtain the original data. Its collision resistance also makes it nearly impossible for different inputs to produce the same hash output. In the future, I would continue to use the Maven Dependency Check tool to identify vulnerabilities.
  
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

  I made certain the application was functional and secure by testing it and ensuring the program ran smoothly. It failed several times, but after I reconfigured it a few times I got it to work. To see if I introduced new vulnerabilities, I ran a second dependency check to identify any changes and ensure the software was more secure than before.
  
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

  Definitely learning how to analyze algorithm ciphers and hash functions to determine which is best for your particular application. This skill will help when working to secure new applications. 
  
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

  I would want employers to see the changes I made to the code, how I introduced a hash function to improve security and the result of a better dependency check showing that I was able to achieve the goal of improving the application's security.
