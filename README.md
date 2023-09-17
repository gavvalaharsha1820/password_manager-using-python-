# password_manager-using-python-
This project aims to create a user-friendly password manager application with a graphical user interface (GUI) using Python and the Tkinter library. The password manager provides users with a secure and efficient way to store and retrieve login credentials for various online services and websites.

Industrial Internship Report on
” Simple Password Manager with GUI”
Prepared by
G.Harshavardhan Sai

Executive Summary
This report provides details of the Industrial Internship provided by upskill Campus and The IoT Academy in collaboration with Industrial Partner UniConverge Technologies Pvt Ltd (UCT).
This internship was focused on a project/problem statement provided by UCT. We had to finish the project including the report in 6 weeks’ time.
My project was about Simple Password Manager with GUI . The Simple Password Manager with GUI is a Python-based application developed using the Tkinter library. It serves as a user-friendly solution for securely storing and managing login credentials for various online services and websites. This project prioritizes ease of use, data security, and a responsive graphical user interface.
This internship gave me a very good opportunity to get exposure to Industrial problems and design/implement solution for that. It was an overall great experience to have this internship.









 
TABLE OF CONTENTS
1	Preface	3
2	Introduction	4
2.1	About UniConverge Technologies Pvt Ltd	4
2.2	About upskill Campus	8
2.3	Objective	9
2.4	Reference	9
2.5	Glossary	10
3	Problem Statement	11
4	Existing and Proposed solution	12
5	Proposed Design/ Model	13
5.1	High Level Diagram (if applicable)	13
5.2	Low Level Diagram (if applicable)	13
5.3	Interfaces (if applicable)	13
6	Performance Test	14
6.1	Test Plan/ Test Cases	14
6.2	Test Procedure	14
6.3	Performance Outcome	14
7	My learnings	15
8	Future work scope	16

 
1	Preface
Summary of the whole 6 weeks’ work.
About need of relevant Internship in career development.
Brief about Your project/problem statement.
Opportunity given by USC/UCT.
How Program was planned
 
Your Learnings and overall experience.
Thank to all (with names), who have helped you directly or indirectly. 
Your message to your juniors and peers.
 
2	Introduction
2.1	About UniConverge Technologies Pvt Ltd
A company established in 2013 and working in Digital Transformation domain and providing Industrial solutions with prime focus on sustainability and RoI.
For developing its products and solutions it is leveraging various Cutting Edge Technologies e.g. Internet of Things (IoT), Cyber Security, Cloud computing (AWS, Azure), Machine Learning, Communication Technologies (4G/5G/LoRaWAN), Java Full Stack, Python, Front end etc.
 
i.	UCT IoT Platform ( )
UCT Insight is an IOT platform designed for quick deployment of IOT applications on the same time providing valuable “insight” for your process/business. It has been built in Java for backend and ReactJS for Front end. It has support for MySQL and various NoSql Databases.
•	It enables device connectivity via industry standard IoT protocols - MQTT, CoAP, HTTP, Modbus TCP, OPC UA 
•	It supports both cloud and on-premises deployments.
It has features to
• Build Your own dashboard
• Analytics and Reporting
• Alert and Notification
• Integration with third party application(Power BI, SAP, ERP)
• Rule Engine

   


ii.	Smart Factory Platform ( )
Factory watch is a platform for smart factory needs.
It provides Users/ Factory 
•	with a scalable solution for their Production and asset monitoring
•	OEE and predictive maintenance solution scaling up to digital twin for your assets.
•	to unleased the true potential of the data that their machines are generating and helps to identify the KPIs and improve them.
•	A modular architecture that allows users to choose the service that they what to start and then can scale to more complex solutions as per their demands.
Its unique SaaS model helps users to save time, cost, and money.
   






iii.	  based Solution
UCT  is one of the early adopters of LoRAWAN technology and providing solution in Agritech, Smart cities, Industrial Monitoring, Smart Street Light, Smart Water/ Gas/ Electricity metering solutions etc.
iv.	Predictive Maintenance
UCT is providing Industrial Machine health monitoring and Predictive maintenance solution leveraging Embedded system, Industrial IoT and Machine Learning Technologies by finding Remaining useful lifetime of various Machines used in production process.
 
2.2	About upskill Campus (USC)
upskill Campus along with The IoT Academy and in association with Uniconverge technologies has facilitated the smooth execution of the complete internship process.
USC is a career development platform that delivers personalized executive coaching in a more affordable, scalable, and measurable way.




























2.3	The IoT Academy
The IoT academy is EdTech Division of UCT that is running long executive certification programs in collaboration with EICT Academy, IITK, IITR and IITG in multiple domains.

2.4	Objectives of this Internship program
The objective for this internship program was to
 ☛ get practical experience of working in the industry.
 ☛ to solve real world problems.
 ☛ to have improved job prospects.
 ☛ to have Improved understanding of our field and its applications. 
 ☛ to have Personal growth like better communication and problem solving.



2.5	Reference
•	Learn Python Book by “Mark lutz”, 4th Edition.


2.6	Glossary
Terms	Acronym
NumPy 	An Open First, I can’t library, that’s used in almost every field of Computer science and engineering
Pandas	A python Library used for working with data set
Json	 A text, written with JavaScript object notation, used to work with Json data.
tkinter	A Standard GUI library for python.

3	Problem Statement
		 In today's digital age, individuals often find it challenging to manage their numerous online accounts and associated login credentials securely. Many people resort to using weak or duplicate passwords, which can lead to security vulnerabilities and compromised accounts. To address this issue, there is a need for a secure and user-friendly password management solution that allows individuals to store, retrieve, and manage their login credentials for various online services and websites.

 
4	Existing and Proposed solution
                                                                                                Password managers have become an essential tool for many individuals and organizations to securely store and manage login credentials. There are several existing solutions available, both as standalone applications and online services. Some popular existing password managers include.
•	LastPass: LastPass is a widely used online password manager that offers browser extensions and mobile apps. It stores and fills in passwords for various websites and provides a secure vault for other sensitive information.
•	1Password: 1Password is a password manager that offers strong encryption, password generation, and secure storage of not only passwords but also credit card information and secure notes.
•	Dashlane: Dashlane is known for its user-friendly interface and offers features such as password generation, secure storage, and a digital wallet for payment information.
•	Bitwarden: Bitwarden is an open-source password manager that allows users to self-host their password vault or use the cloud-based version. It offers secure password storage and synchronization across devices.
•	KeePass: KeePass is an open-source, offline password manager that stores passwords in an encrypted database file. It is highly customizable and is a popular choice for users who prefer complete control over their password storage. 
Proposed solution:
The proposed solution is to create a simple, locally-hosted password manager with a graphical user interface (GUI) using Python and the Tkinter library. This solution aims to provide a lightweight and easy-to-use password management tool for individuals who want to store and retrieve their login credentials securely. The key features of the proposed solution include:
•	User-Friendly GUI: The password manager will have a user-friendly GUI, making it accessible to users with varying levels of technical expertise.
•	Secure Password Storage: Passwords will be securely stored in a local JSON file. While this solution does not include encryption (for simplicity), a more robust implementation should consider implementing encryption for added security.
•	Adding Passwords: Users can add login credentials for different services/websites by providing the service name, username, and password.
•	Retrieving Passwords: Users can retrieve stored passwords by entering the service name. The application will display the username and password for the selected service.
•	Error Handling: Proper error handling will be implemented to provide informative messages to users in case of issues like missing fields or when a requested password is not found.
•	Clear Entries: The application will have an option to clear the input fields after adding or retrieving a password, providing a smoother user experience.
•	Optional Features: Depending on the project's scope and complexity, optional features such as a master password, password generator, and import/export functionality could be added in the future to enhance security and usability.

4.1	GitHub Link: 
             https://github.com/gavvalaharsha1820/password_manager-using-python-.git



4.2	Report submission (GitHub link): 
              https://github.com/gavvalaharsha1820/password_manager-using-python-.git



 
5	Proposed Design/ Model
5.1	High Level Diagram (if applicable)
5.2	Low Level Diagram (if applicable)


     
6	Performance Test

To perform performance testing for the password manager project described earlier, you can focus on measuring its ability to handle many passwords and users efficiently. Here's how you can conduct performance testing for the project.
Performance Test Scenario: Evaluate the project's performance by simulating a scenario where many passwords are added and retrieved by multiple users concurrently.

6.1	Test Plan/ Test Cases

6.2	Test Procedure:
•	Create a GUI using Tkinter that includes input fields for service name, username, and password.
•	Implement functions to add passwords and retrieve passwords from the JSON file.
•	Implement error handling to handle cases where fields are not filled or when a requested password is not found.
•	Securely store passwords in the JSON file (consider encryption for added security).
•	Provide a clear entries button for users to reset the input fields after each action.
6.3 Performance Outcome


 
 
7	My learnings

		UpSkill campus is the first organization that provided me with a free internship. I took the course Python programming learning where I learned many libraries function, modules and packages. I done a project on simple password manager with GUI provided by Upskill, this helped me a lot to know about the modules, packages, implementation of various concepts like this is tkinter, NumPy, pandas. By these concepts and with this project I developed my self-confidence, and I can deal much more projects. The credit is completely for UpSkill Campus. Thanks for providing this internship. I hope in future we continue.

8	Future work scope
         In summary, the future scope of the password manager project involves enhancing security, usability, and functionality. This includes adding advanced security features like biometric authentication and encryption, expanding compatibility with mobile and web platforms, enabling password sharing and collaboration, providing cloud sync and backup options, and integrating with third-party services. Additionally, improving user education, accessibility, and performance, as well as considering open-source development and compliance with data protection regulations, are key aspects of its future development.






