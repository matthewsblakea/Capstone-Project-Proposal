Blake Matthews.

Capstone Project Proposal.

The application I have planned is a ticketing system for a hypothetical computer repair company with multiple physical locations. Through work, I am familiar with tech support ticketing software and the business rules thereof. The other reason I chose this as a project is because making a full-stack CRUD application (without the hypothetical business this is all the software actually is) seemed interesting to me and I thought I would learn a lot.

The business will offer different tech support services as listed in the table below:

![image](https://github.com/matthewsblakea/Capstone-Project-Proposal/assets/149626951/fc57bd82-12cb-4bc1-9ef0-ce78df549fc6)

 
The application will be open enough to facilitate all kinds of devices being serviced from personal computers to a business’s wifi router. Due to inherent limitations, remote consultations could not be performed for physical or hardware repairs, and the effectiveness of remote appointments for software issues would depend on what the issue is e.g. if someone has a corrupted operating system on their computer, no installation media, and is not good at maintaining computers, they would likely benefit from on-site or in-shop work.
	
 
As stated above, the application is CRUD: there is a database where all the data lives, the program logic layer with an API for the front-end, a web front-end for the technicians employed by the company, and a web front-end for customers (typically I would use the word clients but given the technical usage of the word I do not want to confuse). I am writing the program in C#. For the database I am using SQLite. I intend to use entity framework but there is a chance I may change that when I actually start working on the project. I am picking EF mostly because we talked about it in class and staying within the .net environment will make things go smoothly. I plan to use Blazor for front-end development, again because it keeps my project within the .net environment and we talked about it in class. It took a lot of deliberation to decide this as I researched Blazor and started to seriously wonder whether investing time into learning it would be worth it, but my research indicated that Blazor would be a fine fit for a CRUD app, especially one using all .net otherwise.
 
Application Map:

![image](https://github.com/matthewsblakea/Capstone-Project-Proposal/assets/149626951/bdc4aa81-6980-450a-a93c-7083c5df80b4)

DB Map:

![image](https://github.com/matthewsblakea/Capstone-Project-Proposal/assets/149626951/bf1ef342-45c5-4bf9-ac25-e5cc1587a067)

DB Schema:

![image](https://github.com/matthewsblakea/Capstone-Project-Proposal/assets/149626951/70aba5a2-63b0-4036-aece-b2b49df22be6)
