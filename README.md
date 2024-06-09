[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15222086&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:

A branch in Computer Science that involves developing, testing, and deploying computer aplications to solve world problems.

What is software engineering, and how does it differ from traditional programming?
Software Development Life Cycle (SDLC):

A SDLC is a Software enginnering framework the focuses on structured phases and steps to manage the software development process.

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

There are 7 phases of the SDLC,
1. Planning: The objectives of this phase are to determine the project scope, objectives of the project, resources tht will be needed, timelines and the feasibility of the project. In this phase the overall planning of the project takes place, the risk analysis, cost estimations and how the resources will be allocated.
2. Requirements Analysis: The objective of this phase is to gatherand analyze the requirements of the software from the stakeholder and end users.These requirements are gathered throught interviews, surveys, and observations.
3. Design: The objective of this phase is create the architecture and detailed design of the design of the software based on the requirements. These can be achieved by system designs, database designs, interface designs and creating deisgn documents and prototypes.
4. This is the coding phase. The objective is to convert the design into code by writing code using appropriate programming languages and tools, following coding standards and guidelines.
5. Testing: This phase is the verify that the software functions as intended and it does not have any defects. The testing is done using unit testing, intergration testing, system testing, acceptance testing, and fixing bugs.
6. Deployment: In this phase the sofware is released to the production environment where it can be used by end users. This is done by installation, configuration, and providing user training and documentation.
7. Maintanance: The objective of this phase is to update and improve the software to fix issues, enhance functionality, and adapt changes according to the changing  requirements.

Agile vs. Waterfall Models:
Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

Agile Model.
* Agile breaks down the project into small manageable increments called sprints or iterations, which typically last 1-4 weeks.
* It emphasizes flexibility and customer collaboration. Requirements can evolve throughout the development process.
* Continuous feedback from stakeholders and users is incoporated at the end of each iteration.
* Teams are well organized ad cross-functional, with all the skills needed to complete tasts within the iteration.
Phases of the agile model:
1. The requirements are gathered continuosly and new requirements can be added based on the feedback from stakeholders.
2. Designing is iterative and can evolve over time
3. Developement happens in sprints i.e. short cycles.
4. Testing is doen continuously withing each sprint.
5. Deployment is done reqularly at the end of each sprint or iteration.
6. The product is reviewed after every iteration and adjustments are made.

Scenario: Agile
A company developing a new mobile app with the constantly changing market demands and user feedback would benefit from Agile. The ability to adapt and iterate quickly allows the team to align the product closely with user needs and market trends.

Waterfall Model.
* The waterfall model follows a linear and sequential approach where each phase must be completed before the next one begins.
* The requirements are gathered at the beginning of the project and they reamin fixed throughout the project.
* Emphasizesn comprehensive documantation at each phase
Phases of waterfall model:
1. Gathering and documenting all requirements before development starts.
2. The creation of the overall system architecture is based on the requirements.
3. Writing code the is based on the design.
4. A fully developed system is deployed to production.
5. Fixing issues and making updates as needed.

Scenario: Waterfall Model:
A project with well-defined, stable requirements and strict regulatory and documentation needs would be suitable for the Waterfall model. The predictable, structuredd approach ensures compliance and thorough documentation.

KEY DIFFERENCES:
Agile model breaks down the project into small manageable sprints whereares the waterfal model follows a linear sequential approach where each must be completed before moving on to the next one.

Requirements Engineering:
What is requirements engineering? Describe the process and its importance in the software development lifecycle.

A systematic process used in software engineering to define, document, and maintain the requirements of a system. It has phases which aim to understand what the stakeholders need and ensure that the final system meets those needs. (Lamsweerde,2000)
The phases are:
1. Elicitation: In this phase we gather requirements from stakeholders, users, and other sources by conducting interviews, surveys, workshops, observatios, and use cases. The tools and techniques used to conduct these activities are brainstorming sessions, focus groups, prototyping, and requirement workshops.
2. Analysis: The objective here is to analyse and refine the requirements gathered during the elicitation phase and to understand their efasibility, consintency, and implications. The analysis can be done throught identifying conflicts, prioritizing requirements, and establishing feasibility. The tools and techniques for the analysis include data flow diagrams, entity-relationship diagrams, and modeling tools.
3. Specification: Here we use structured or semi-structured templates, natural language, and modeling notation to create requirement specification documents such as Software Requirement Specification (SRS) in other to document the requirements in a clear and detailed manner.
4. Validation: In this phase, the objective is to ensure that the requirements accurately reflect the needs of the stakeholder and are feasible for implementation. This can be achieved by reviewing the requirements with the stakeholders, perfoming requirement walk-through and conducting inspections. The tools and technique used are requirement review meetings, prototypes and simulations.
5. Management: This phase is where the requirement changes are managed throughout the project lifecycle by tracking requirement changes maintaining traceability, and managimg requirement versions. Requirement management tools, version control systems, and tracebility matrices and some of the tools and techniques that can be used in managing the process of requirement engineering.

Requirement engineering is important because it:
- Provide clarity and understanding to both the development team and the stakeholders on what the system should do
- Potential issues and risks can be identified esrly in the project, this reduces the chances of costly changes later.
- Helps manage the scope of the project by clearly defining what is included and excluded.
- Ensures that the requirements are complete , consistent, adn testable leading to higher-quality software.
- Ensures that the final product meets the needs and expectations of the stakeholders.

Software Design Principles:
Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

Modularity refers to the design principle of dividing a software system into distinct, independent components or modules, each which performs a specfic function or set of functions. These modules can be developed, tested, and maintained separately and then intergrated to form the complete system.

Modularity improves maintainability of software systems in the following ways:
- Modules are independent, therefore changes to one module can be made without affecting others resulting in easier updates and modifications of the sofware.
- Bugs and issues can be isolated within individual modules, making it easy to identify and fix problems.

Modularity improves scalability of software systems in the following ways:
- New features and functionalities can be added by developing new modules or updating existing ones without rewriting the entire system.
- Different teams can work on different modules at the same time, this results in an increase in the development process and this allows the system to scale more efficiently.
- 

An example of Modular design in practice: A shopping cart module, it manages the user's cart, including adding, removing, and updating items.

Testing in Software Engineering:
Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

1. Unit testing: It is done at the lowest level. It tests the basic unit of software, which is the smallest testable piece of software, and is often called "unit", module, or "component" interchangeably. It is done by developers using tools like JUnit,NUnit, pytest, etc.
2. Integration testing: It is performed when two or more tested units are combined into a larger structure. The test is often done on both the interfaces between the components and the larger structure being constructed, if its quality property cannot be assessed from its components. This test is conducted by testers or developers using tools like JUnit,NUnit, pytest, etc.
3. System Testing: Tends to affirm the end-to-end quality of the entire system. System test is often based
on the functional/requirement specification of the system. Non-functional quality attributes, such as reliability, security, and maintainability, are also checked. The tests are conducted using Selenium, QTP, LoadRunner, etc.
4. Acceptance Testing: It is done when the completed system is handed over from the developers to the customers or users. The purpose of acceptance testing is rather to give confidence that the system is working than to find errors. The testing is done using custom scripts and end-user feedback.
(Lou,2001)

Testing is crucial in Software Development because it:
-  Ensures that the software meets the quality standards and it works as expected.
- Rigorous testing helps ensure that the software performs reliably under different conditions, enhancing user trust and satisfaction.
- Detecting and fixing issues early in the development process is more cost-effective than addressing them after deployment.
(Sawant, et.al, 2012)

Version Control Systems:
What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

VCSs are tools that help manage chanegs to source code and other project files over time. They allow multiple developers to collaborate on a project, track changes, and revert to previous versions if necessary. VCSs are essential for maintaining the integrity and history of code, facilitating teamwork, and improving project management. (Zolkifl, et.al. 2018)

1. Git  -  Every developer has a full copy of the repository, including the history.
        - Lightweight branching and merging capabilities.
        - Fast performance for local operations like commits, diffs, and branches.
        - Allows developers to stage changes before committing.
        - Popular hosting services that provide additional features like pull requests, issue tracking, and CI/CD pipelines.
2. Subversion (SVN) - Single central repository that all developers sync with.
                    - Ensures that all changes in a commit are applied or none at all.
                    - Tracks changes to directories as well as files.
                    - Better handling of binary files compared to some other VCSs.
                    - Fine-grained access control over who can read or write to specific parts of the repository.



Software Project Management:
Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

A Software Project Manager is responsible for planning, executing, and closing software projects. They oversee the project team, manage resources, schedule tasks, and ensure that the project meets its goals within the specified timeline and budget. The role involves coordinating various aspects of the project, from requirements gathering to delivery, and ensuring that all stakeholders are aligned and satisfied.
Responsiblities:
1. Project Planning - Define project scope, objectives, and deliverables. Developing detailed project plans, including schedules, milestones, and resource allocation. Identifying risks and develop mitigation strategies.
2. Team Management - Assembling and lead the project team assigning roles and responsibilities. Fostering a collaborative and productive team environment. Providing guidance, support, and motivation to team members.
3. Resource Management - Allocating and manage resources (e.g., budget, personnel, equipment). Ensuring that there's optimal use of resources to meet project goals.
4. Communication - Serving as the primary point of contact for stakeholders, including clients, team members, and upper management. Communicating project status, progress, and any issues or changes. Facilitating regular meetings, such as stand-ups, reviews, and retrospectives.
5. Project Closure: Conducting project reviews and retrospectives to identify lessons learned. Ensuring that all project deliverables are completed and approved. Closing out the project formally and hand over deliverables to the client or end-users.

Challeneges: 
There are several challenges faced by software project managers, such as scope creep, resource constraints, and stakeholder management.

Software Maintenance:
Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

Software Maintenance is the process of modifying and updating software applications after their initial development and deployment. The goal is to correct faults, improve performance, adapt the software to a changed environment, and ensure that it continues to meet user needs and business requirements.

Types of Software Maintenance:
1. Corrective Maintenance - The objective is to fix identified defects and bugs in the software.
2. Adaptive Maintenance - In this type the objective is to modify the software to keep it compatible with changing environments.
3. Perfective Maintenance - The objective is to enhance the software by improving performance or adding new features based on user feedback.
4. Preventive Maintenance - The objective is to make changes to prevent future problems or to improve the software’s maintainability.

Regular maintenance helps keep software up-to-date, reliable, and aligned with the ever-changing technological landscape and user requirements.

Ethical Considerations in Software Engineering:
What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

Ethical issues in Software Engineering:
1. Privacy and Data Security - Handling personal and sensitive information responsibly to protect user privacy. Ensuring data is stored securely and transmitted safely to prevent unauthorized access and breaches.
2. Intellectual Property - Respecting intellectual property rights and avoiding plagiarism. Properly licensing software components and acknowledging the work of others.
3. Quality and Reliability - Ensuring software is reliable, performs as expected, and is free of significant defects.Avoiding shortcuts in development and testing that could compromise software quality.
4. User Consent and Transparency - Providing clear and accurate information about how user data will be used. Obtaining informed consent from users before collecting and processing their data.
5. Bias and Fairness - Avoiding bias in algorithms and ensuring fairness in automated decisions. Testing for and mitigating biases that could harm certain groups of users.
6. Social Impact - Considering the broader social impact of software, including potential harm or misuse. Avoiding the development of software that can be used for malicious purposes.
7. Professional Responsibility - Upholding professional standards and adhering to best practices in software development. Continuously updating skills and knowledge to stay current with industry standards.
8. Conflict of Interest - Avoiding situations where personal interests could conflict with professional responsibilities.
Disclosing any potential conflicts to relevant stakeholders.
9. Sustainability - Considering the environmental impact of software development and usage. Promoting energy-efficient practices and sustainable software solutions.

Ensuring Adherence to Ethical Standards in Software Engineering

- Adopt Professional Codes of Ethics: Follow guidelines from organizations like ACM and IEEE for professional conduct and ethical decision-making.
- Practice Transparency: Be clear with users about data collection, usage, and security, providing accessible privacy policies and terms of service.
- Implement Security Best Practices: Use encryption, secure coding, and regular security audits to protect data, and stay updated on emerging threats.
- Ensure Fairness and Avoid Bias: Test algorithms and data sets thoroughly to identify and reduce bias, and involve diverse teams for multiple perspectives.
- Prioritize Quality: Adhere to rigorous testing and quality assurance to ensure reliability and performance, avoiding shortcuts.
- Continuous Learning and Professional Development: Keep up with technological advancements and ethical considerations through ongoing education and training.
- Respect Intellectual Property: Use open-source and third-party software according to their licenses, and credit appropriately. Avoid unauthorized copying.
- Engage in Ethical Decision-Making: Consider the broader impact of software decisions and seek diverse stakeholder input.
- Promote a Culture of Ethics:Foster a workplace that values ethical behavior and open communication, encouraging team members to report ethical concerns.
- Seek Guidance and Collaborate: Consult with colleagues and ethical review boards when facing dilemmas, and work with others to develop ethical practices.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
