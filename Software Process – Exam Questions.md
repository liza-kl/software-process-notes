#preview-questions #software-process #exam

## Preview 1
- ==*What are key characteristics of Open Source Software Development==* 
	- [[@abrahamssonAgileSoftwareDevelopment2002#^83492e]]
		- - ==🔥 *How is the OSS method characterized?==* ^83492e
		- "a massive parallel development and debugging effort"
		- The systems are built by potentially large numbers of volunteers 
		- Work is not assigned; people themselves choose the task they are interested in 
		- There exists no explicit system level design 
		- There is no project plan, schedule or list of deliverables
		- The system is augmented with small increments
		- Programs are tested frequently
	- [[@sadowskiModernCodeReview2018#2.2. Convergent Practices in Code Review]]
		-  **Contemporary peer review** follows a lightweight flexible process
		- **Reviews can happen early** (before a change is committed), quickly and frequently
		- **Change sizes are small**
		- **Two reviewers find an optimal of defects**
		- **Review has changed from a defect finding activity to a group problem solving activity**

	- According to Linus Rules: [[Software Process – Methods History Lecture Notes Week 2#^4b0868]]
  
- ==*What are the similarities and differences between the method proposed by Royce and RUP==*
	- [[@abrahamssonAgileSoftwareDevelopment2002#^04b462]]
	- [[@royce1970]]
	- **Similarities:**
		- Analysis step: Is the inception phase in RUP and the first 3 steps in Royce
		- **Goal** Both aim to guide the software development process and produce a high-quality product.
	- **Differences**
		- **Documentation:** Waterfall relies on heavy documentation, whereas 
		- **Testing**: RUP does not have a specific step for testing, whereas Royce has intended that
		- **Iteration**: Royce sees iteration between preceeding or subsequent steps whereas RUP has the iteration multiple times within one phase. 

-  ==*Analyze the complexity of the digital system for the new environment act using the TOE framework==*
	- [[@bosch-rekveldtGraspingProjectComplexity2011]]
	- *Technical, Organizational, and Environmental (TOE) framework to assess the complexity of engineering projects. Using the TOE framework, the complexity of engineering projects can be assessed from technological complexity (related to goals, scope, tasks, experience, and risk), organizational complexity (related to size, resources, project team, trust, and risk), and environmental complexity (related to stakeholders, location, market conditions, and risk)*
	- **Technical**:
		- **Goals**: A lot
		- **Scope largeness**: Huge, because they wanted to consolidate a big law 
		- Different form standards, file standards to work with 
		- Consistency between objects and text, huge variation in data
	- **Organizational**:
		- A lot of municipalities and end users which need their "own" solutio to create the connection to the data.
		- Multiple authorities which ahve to work
	- **Environmental**: 
		- **Market Conditions**: We also do not have to deal with that 
		- **Location:**  We do not have to deal with weather or location conditions, since this is a digital project (maybe not building the data center directly next to the sea)
		- **Political Influence**: The political influence does influence this project, because there is a fix deadline until when this project should go live (but this can also happen in any other project as well.. because of the law ? dunno if this is actually political influence)
		- **Stakeholders**: A lot of stakeholders (municipalities), can be seen as a stakeholder because they have to build on top of their systems. Government gives the money, the dedicated ministry
- Why did the external view from the Leibniz institute yield that the plan was "okay" for the environmental act?
	- Confirmation bias
	- No real authority. The Leibinz person had a general understanding but was not an expert in the field -> False assurance
-==*Other notes regarding dso in Lec 1==*
	- [[Software Process – Lecture Notes Week 1]]

- ==*How could a radical agile approach look like to realize the digital system for the environment act==*
	- Ask, if we really need it 
	- Starting with a MVP and expose it (with the simplest solution)

	- ![[Pasted image 20240321135944.png]]
- Radical Agility focuses on Self Organization, The social value of product of service, impact of living beings and becoming the desired change.
- In orther to do that, we would need competent people, 

- ==*How could a radical agile approach look like to realize the digital system for the environment act==*
	- Feedback Loops, 
- ==*What is the contingency theory==*
	- [[@zhuDiscoveringComplexityEmergent2017#^30753f]]
- ==*Name three practices to scale agile development==*
- [[Software Process – Methods History Lecture Notes Week 2]]
- ==*How to take ownership in a group when you don't want to be "loud"==*
	- Building relationships with individuals to get the information. Practice active listening, build trust 
	- Stand up with knowledge – think long term, which trade offs does your solution have. Provide alternatives, think out of the box. 
	- With Skill 
	- With Attitude
- ==*How can you recognize the value of a good idea?==*
	- Like in OSS having core maintainers
- ==*What are the challenges of Applying Large scale Agile methods?==*
	- Inter Team Coordination
	- Organisational Structural Challenges
	- Architectural Challenge
	- Requirements Engineering
	- Customer Colaboration
## Preview 2 
- *==Assume agility is the ability to timely adapt to be successful. Explain what is needed to be agile.*==
	- *timely adapt*: Feedback that helps to identify what is valuable to the business. 
	- A team that is capable to learn and to adapt to the changes 
	- A team which can get the right feedback at the right time, therefore probably establishing needed metrics
	- Having test cases to set assumptions (reference classes)
	- *The right amount of team empowerment*. Although bureaucracy increases fairness, we need some sort of empowerment that team members can take decisions on their own to be not too late when executing something

- ==*What is meant by being agile?==*
	- Being able to make changes and do what is needed to be successful
	- "Do what needed to be successful" – Do we even need to do something? Proove necessaty
- ==*Explain how it could be that a software development project can be seen as NOT agile, even while it conforms to Scrum==*
	- Scrum is a management framework, it does not entail "agile" values out of the box. The agility comes from the culture within a team or a company. 
	- If you have a team which is not able to react to change or process feedback adequately, you already missing out on the principle of Agility ,being able to respond to change timely. Or if your company just does not have enough knowledge in that sphere (e.g. Nokia vs Apple)
	- If you endorse Scrum but have a management which does not want to work in a flat hierarchy or give autonomy / enough level of empowerment to the team you are also not going to succeed
	- "*The secret to success is not the method, it depends on the organization and if it can make it work in that context*"
	- Can you deliver code on time?

- *==Which of these are part of RUP*==
	- [[Software Process – Methods History Lecture Notes Week 2#^7ade2f]]
	- Upfront Design, Executable Architecture, Working in Iterations, Documentation

- ==*What is strategic planning?==*
- ==*What is tactical planning?==*
-  ==*In the paper "Planning to Fail: When Is Project Planning Counterproductive?" several arguments are provided to explain why planning is not effective and sometimes counterproductive. Provide these arguments.==*
	- [[@zwikaelPlanningFailWhen2023#^0af162]]

-  ==*Explain how a bureaucracy achieves fairness==*
	- [[Software Process – Organization Lecture Notes Week 3]]
	- **Hierarchy** – The spheres of competence and divisions of labor are clearly defined
	- **Continuity** – A structure where administrators have a full-time salary and advance within the structure 
	- **Impersonality** – Prescribes rules and operating rules rather than arbitrary actions 
	- **Expertise** – Officials are chosen according to merit, have been trained and hold access to knowledge
	- *bureaucracy can promote diversity within government organizations and, more broadly, social equity throughout the nation*
	- Protects people from *arbitrary decisions* inside the organization
	- Provides scope for decision making and boundaries 
	- 
-  ==*Explain the CEPC framework==*
	- [[@zhuDiscoveringComplexityEmergent2017]]

-  ==*Illustrate what is meant with **emergence in the context of software engineering**==*
	- [[@zhuDiscoveringComplexityEmergent2017#^93b77d]]
	- The concept of emergence refers to **phenomena that occur on a system level without being present at the level of elements in the system**. 
- ==*What is the significance of the costs of defects at different times of a project lifecycle?==*
	- [[@bossavitLeprechaunsSoftwareEngineering2015]] [[@menziesAreDelayedIssues2017]]
	- According to Boehm, it raises exponentially. However, this hypothesis was not really grounded. All following work has been build upon that seminal paper.
	- “a defect is any change to a product, after its construction, that is necessary to make the product correct.” (Menzies et al., 2017, p. 1914)**
	- However, Literature agrees that **requirements change can be expensive, but that the effect depends on the process used (e.g., agile vs. waterfall) and the adaptability of the system 
 - *==Mathieu mentions boundary spanning as relevant for team effectiveness. Explain this.==*
	- [[@mathieuEmbracingComplexityReviewing2019#^e0c656]]

## Complexity Questions

- *==What is the complexity of the OpenGov project?*==
	- Scale of the project, variety in end users (900 different )
	- One solution probably not good (technical diversity)

	- ![[OpenGov_Assignment (1).pdf]]
- ==*What is the complexity of the environmental law?==*
	- No one has ever done that before in the Netherlands – first time of doing this makes it a higher risk
- ==*What is the complexity of the failed case?==*
	- The main complexity in the Boeing 737 case can be referred to the dynamic complexity in terms of human errors and behaviour 
	- Other than that it was probably complicated but not complex 
- *==What is the impact of uncertainty?*==
	- *uncertainty is considered as an inherent element of project complexity. Uncertainty could affect both detail and dynamic complexity in projects.* [[@zhuDiscoveringComplexityEmergent2017]]
	- Budget explosion, time overrun but can also be positive that you are done faster
- ==*Explain the concept of emergence and how to handle this==*
	- Emergent behaviours are the traits of a system that are not obvious or apparent from the individual components in isolation, but that occur as a result of the interactions, dependencies, and relationships that form when they are placed together in a system 
	-  modelling–experimenting–learning
	- Making the problems smaller

## Project Methodologies 

-  ==*Project size and coping with new insights (volatility) are some of the most important success factors, explain how the different methods manage these==*

	-  **Royce**:
		- [[@royce1970]]
		- **Size**: In terms of size Royce proposed different models, going from the simple "analysis" and then "coding" step (if you have one single person building the software). For larger projects he sees iteration between successive setps. However, the paper did not specify "size"
		- **Volatility**: involves sequential phases of development, which may struggle to accommodate changes in project size or volatility due to its rigid structure and limited opportunities for feedback and iteration.
		- Does not allow for a change in requirements / goals in later stages of the project for smaller projects. In bigger ones you can have the iteratiion
		- Royce wants to combat that with a Preliminary Program design 
		- ![[Pasted image 20240324085246.png]]

	- RUP: The Rational Unified Process (RUP) incorporates iterative development and flexible phases, allowing for some adaptation to project size and volatility through its iterative nature and emphasis on continuous refinement.

	- Scrum: Scrum copes with project size and volatility by enabling adjustments through user stories that can be adapted by the Product Owner, sprint planning sessions, daily syncs, and regular retrospectives, facilitating flexibility and responsiveness to change.

	- Lean:
		- Size: Lean focuses on the whole, by looking at the customer needs. The principles can also be used for bigger projects 
		- Volatility: Lean principles emphasize continuous learning and small, just-in-time (JIT) production, which can help manage project volatility by enabling rapid adjustments and minimizing the impact of failure through incremental and iterative delivery. Therefore requirements can be adjusted 

	- XP: Extreme Programming (XP) emphasizes practices such as continuous integration, test-driven development, and pair programming, which enable teams to manage project size and volatility by promoting frequent feedback, collaboration, and adaptation to changing requirements.
-  ==*What are the fundamental elements of Scrum, RUP, Royce's model, LEAN*==
	- [[@abrahamssonAgileSoftwareDevelopment2002]] [[@royce1970]] 

- ==*Why does RUP not guarantee project success?==*
	- In general, it is not about the method *has no **situational** knowledge. In an organization methods are adapted or emerge to include specific characteristics*.
	- The secret to success is not the method, it is **the ability of the organization to make the method work** [[Software Process – Methods History Lecture Notes Week 2]] 


- ==*Why can a project using pure Scrum still proof NOT to be agile?==*
	- Agile is about *having the ability to adapt to changes quickly and process feedback in way to create value*
	- According to the principles of agile it is about to do the things that are needed and not doing the things that are not needed. 
	- If your company does not have the inherent *agile* culture based on the agile principles, it won't work out (example Nokia)
	- If you do not have the right people, only doing the meetings without any value outcome and dont use practices as like from XP, your basically can label yourself scrum.

- ==*What makes it hard to organize good feedback?==*
	- [[Software Process – Organization Lecture Notes Week 3#^f53f9d]]
	- Lecture from Agility 
	- We need feedback that demonstrates if the software we create will enable the company to reach its goals
	- What is valid feedback – how can we distinguish from valid feedback and "stakeholder applause"
	- Good Feedback should not disturb the development "flow" – which it can if you use a lot of it 

- ==*Overview on the whole is an important factor for project success, how is this addressed by the different methods==**
	- ***Scrum**:  Scrum provides transparency and visibility through its artifacts, including the Product Backlog, Sprint Backlog, and Burndown Charts. Daily Stand-up meetings ensure that the team is aligned and provides an overview of progress and impediments.
	- **RUP**: RUP emphasizes comprehensive documentation, including vision documents, project plans, and detailed requirements specifications. These artifacts provide stakeholders with an overview of the project's objectives, scope, and milestones
	- **SAFe**: 
	- **Spotify**:
	- **XP**:
	- **LEAN**: 1. - Lean focuses on delivering value to the customer efficiently. Visual management tools such as Kanban boards provide a clear overview of work in progress, bottlenecks, and flow, enabling stakeholders to understand the project's status and make informed decisions.
	- Royce / Waterfall: 1. - Waterfall relies heavily on upfront planning and documentation to provide an overview of the project's scope, requirements, and timeline. Detailed project plans, Gantt charts, and milestone reviews help stakeholders track progress and ensure adherence to the predetermined schedule.

- ==*Explain how the cost of defects at different points in the life cycle is an important consideration for the amount of upfront planning==*


- ==*Explain how the cargo cult can be seen as success from an agile perspective==*
	- Agility acknowledges that we might not know our goals upfront, making it feasible to change one's goal during the project 
	- After the Americans legt, Cargo Tribal Leaders stepped up to 
	- **Focus on tangible outcomes**
	- **Incremental Improvement** – The Cargo people lea

## **Empirical Software engineering**

-  How is best practice X being applied and what is the impact?
	- **Resolving Issues Early**: 
	- **Brook's Law, Small Teams**: [[@goteBigDataBig2022]] [[@killaleaSecondConversationWerner2020]]
	- **Fault Analysis tools:**
	- **Amazon S3 Principles**
	- **Code Review**: [[@sadowskiModernCodeReview2018]], you have a contemporary peer review with a max of 2 people. The impact is that people learn from code reviews or learn to teach, maintain established norms, gatekeep. People learn to take ownership for their code and how to write readable code. Application is describe here: [[@sadowskiModernCodeReview2018#^e45954]] Impact described here: 
	- **Microservices**: [[@valeDesigningMicroserviceSystems2022]]
		- Impact: If you use Microservices right you could get Maintainability, Performance, Scalability, Availability, Security, Monitorability
		- Negative Impact: Complexity, Single Point of Failure, Operational Complexity 
		- Application: Multiple Patterns applied in the implementation phase 
- ==*How do we research this best practice and what are the limitations of the research.==*
	- **Team Sizes**: [[@goteBigDataBig2022]], it all depends on the quality of the data, population validity, construct validity and ommited variable bias – it all comes done to the human 
	- **Microservices**: The terms of scalability, performance, maintainability are hard to define allowing different thresholds or globally agreed on concrete metrics to validate the results.  Basically by observing the people, mining data or whatsoever. However, people are mostly not aware that they are using those kind of practices.
- ==*Software Engineering is about making the right trade offs, explain this==*
	- A trade-off is a situation where you have to choose between two or more alternatives that have different advantages and disadvantages. In software engineering those trade offs could 
	- In Software Engineering, trade offs can be trading a solution which is simpler to maintain against performance  

## Organizing is humans working together 

- Explain why most people don’t act adequately when something “bad” happens
	- [[@mcshaneOrganizationalBehavior2018#^447d9c]]
	- Information gatekeeping can keep their position and avoiding consequences – Power
	- Saving status and reputation, We are social creatures
	- Diffusion of responsibility refers to the fact that **as the number of bystanders increases, the personal responsibility that an individual bystander feels decreases** – bystander effect 

- ==*How do bureaucracies ensure fairness==*
	- [[Software Process – Organization Lecture Notes Week 3#^979a74]]

- ==*Which of the basic assumptions of scientific management do not hold for SE (the ones that do are part of our methods)==*
	- The dynamic, creative, and collaborative nature of software engineering requires a different approach to management and organization compared to traditional manufacturing industries (which is linear, static, repeating itself over and over again). You can't compare manufacturing with SE.
	- Also see: [[Software Process – Organization Lecture Notes Week 3#^414012]]

	1. **Standardization of Work Methods**: Taylor advocated for standardizing work methods to improve efficiency. However, in software engineering, tasks can vary significantly in complexity and context. While certain development processes and best practices exist, rigid standardization may not be feasible or effective due to the creative and problem-solving nature of software development
	2. **Piece-Rate Incentive Systems**: Taylor proposed that workers should be compensated based on their output, typically measured by the number of units produced. In software engineering, measuring productivity based solely on output metrics (such as lines of code written) can be misleading and may incentivize the wrong behaviors. Quality, collaboration, and innovation are often more important than sheer output quantity.
	3. **Management Control of Work**: Taylor advocated for tight management control over work processes to ensure adherence to standards and efficiency. However, software development often requires autonomy and self-organization among team members to foster creativity, innovation, and problem-solving. Micromanagement can stifle creativity and demotivate team members.
	4. **Division of Labor**: Taylor proposed breaking down tasks into smaller, specialized components to increase efficiency. While some division of labor exists in software engineering (e.g., roles like developers, testers, and designers), excessive specialization can hinder collaboration and cross-functional learning. Agile methodologies often emphasize the importance of cross-functional teams working collaboratively to deliver value.
	5. **Scientific Selection and Training of Workers**: Taylor believed in scientifically selecting and training workers to perform tasks efficiently. While training and skill development are important in software engineering, the rapidly evolving nature of technology means that skills can quickly become outdated. Continuous learning, adaptability, and problem-solving abilities are crucial in software development.
	6. **Close Supervision and Standardization of Tasks**: Taylor advocated for close supervision of workers to ensure adherence to standardized methods. However, in software engineering, creativity and innovation often flourish in an environment of trust and autonomy. While some level of oversight is necessary, excessive supervision can inhibit productivity and morale.



- ==*Explain why it could be good for motivation to work in a scrum based project, based on Self Determination Theory.==*
	- Self Determination theory assumes that we need some sort of autonomy, competency and connection/ relatedness to perform well  
	- **Autonomy**: In a truly agile Scrum implementation, developers decide what to do and when together in a team. The action of doing it together in a team, one can create more relatedness and connectness

- ==*Explain why it could be bad for motivation to work in a scrum based project, based on Self Determination Theory.==*
	- **Too detailed goals**: If we have user stories which prescribe a goal but also the exact implementation, we lower the autonomy of the developer to decide how to implement that, potentially lowering the motivation
	- **Too ambitious goals**: If Scrum is not done right, and the PO sets too ambitious goals in the user stories which not align with the competence of the person that could be bad
	- **Not having goals at all**: If the scrum goal is to finish all the work in the sprint that won't motivate the people. They cant perform identification
	- Not truly intrinsic motivation: You might be only motivated because of the money 
- [[@ryanIntrinsicExtrinsicMotivation2020]]
## Planning

- ==*What is the planning that happened to realize the IT for the Environment Act / Planning Act / Environmental Planning Act ==*
	- Mostly strategic, little adjustments over time
	- **2011 - 2015 Political Alignment**: Working out an idea, law, milestones 
	- **2011 - 2016 Preparation and Start Realization**, Having a Vision / Business Case, Information Analysis for everyone, Client Contractor ... 
	- 2016 - Switching to Safe Agile with 10 Product Increments, 5 Sprints 1 Slack, 2019 Realizing ambition level 2 (satisfying requirements), realizing final goal in 2024.
	- 2017 Intervntion because it was too complex 

- ==*What in the planning made the project grow too complex and run out of time and budget. (Lecture 2 Slide 2017 audit BIT / Ac ICT? ) ==*
	- [[Software Process – Methods History Lecture Notes Week 2]] [[Software Process – Lecture Notes Week 1#^ef4eb0]]
	- **The Standard which was not ready** – Work approach was not proven, underestimating how much time it takes to establish a new standard
	- **First attempt to automaticaly consolidate law**
	- **Ambition to make law understandable for all is unrealitic**, solution very costly 
	- **Global Problem of Requirements**: Will it really help? Will be asked in 2 years, Goals were ignored, exotic demands 
	- The missing foundation of test data or reference case, not enough research has been done what others did in the world 
	- Way too many teams – From Day 1 scaling up to 14 teams, who did not know each other and had to work together
	- no one asked, if digilization the whole thing is even the correct approach – Why do you need it to make this law a reality? 
	- The architect who did not consider any other solutions than just the microservices, Architecture was not suitable 
	- There was no external view on the architect's decision, not enough feedback. No reliable way to test the software 
	- No one was standing up when asked "is it going okay?"
	- The contracts lost a lot of time 
	- Not asking the municipalities – do they need one solution, a standard software? 
	- Interdependencies of contractors 
	- Not focusing on the "top permits"
- ==*What is the essence of a good plan==*
	- Having a solid foundation which justifies the undertaking
		- Business Case, Feasibility Study, having a game plan to follow, Reference classes and MVP
	- Being able to accept change and able to
	- Having an evolutionary path and continous learning approach
- ==*Explain what entails a business case==*
	- How much will it cost? How much will you get back?
	- [[@einhornAchievingStrategicBenefits2019#^40a3b3]]
- ==*Explain what entails a feasibility study==* 
	- Schedule Feasibility, Economic Feasibility, Technical Feasability, Organizational Feasibility 
	- ![[Pasted image 20240324105135.png]]
	- [[@mcleodFeasibilityStudiesNovel2021a#^294e70]]
-  ==*How can a plan make a project fail==*
	- If you use formal planning where it is not suited, which can erase creativity in people 
	- Not having expertise, coordinated efforts, and ability to learn
	- If the fundament for a plan was a poorly researched feasibility study, poorly created business case (not well-informed investment). *Feasibility studies that are erroneously positive or optimistically biased thus risk causing the implementation of projects that result in losses* [[@mcleodFeasibilityStudiesNovel2021a]]
- 
- ==*Why and how do we try to ensure business IT alignment. Why do the old agile approaches not suffice?==*
	- [[@coltmanStrategicITAlignment2015]]
	- **Why**: IT alignment is used to transform organizations, or making them more efficient, ensuring that their values are achieved and no money is lost. Inflexible links between Business and IT. IT alignment has a positive effect on the agility of a company (which is needed in globalization, digitzation and agility).
	- **How**: 
		- Achieving IT and business alignment involves ensuring that the IT strategy and initiatives are closely integrated and supportive of the overall business strategy and objectives. Here are some key steps to facilitate IT and business alignment:
		-  **Understand Business Objectives**: IT leaders need to have a deep understanding of the organization's business goals, strategies, and priorities. This understanding forms the basis for aligning IT initiatives with the broader business objectives.
		- **Collaboration**: Foster collaboration between IT and business stakeholders. Regular communication and collaboration help in ensuring that IT projects and investments are in line with the needs and priorities of the business.
		- **Develop an IT Strategy**: Develop an IT strategy that is closely aligned with the overall business strategy. The IT strategy should outline how technology can support and enable the achievement of business goals.
		- **Governance**: Establish IT governance mechanisms to ensure that IT investments, projects, and activities are aligned with business priorities. This includes setting up processes for decision-making, prioritization, and monitoring of IT initiatives.
		- **Performance Measurement**: Define key performance indicators (KPIs) that measure the impact of IT on business outcomes. Regularly track and evaluate the performance of IT initiatives against these KPIs to ensure alignment with business objectives.
		- **Change Management**: Implement effective change management practices to ensure that IT initiatives are successfully adopted and integrated into the business operations. Engage stakeholders across the organization to manage resistance to change and ensure smooth implementation.
		- **Continuous Improvement**: IT and business alignment is an ongoing process. Continuously review and adjust IT strategies and initiatives to ensure they remain aligned with evolving business needs and market conditions.
	- **Old agile:** Old agile approaches such as RUP or XP are more focused on the technical side of things, frameworks for creating *software*.  

- ==*What is **Business Agility**?*==
	- Business Agility is **a set of organizational capabilities, behaviors, and ways of working that affords your business the freedom, flexibility, and resilience to achieve its purpose**.
- *==What are the four **core principles behind Agile**?==*
	- **Individuals and interactions over processes and tools.**
	- **Working software over comprehensive documentation.**
	- **Customer collaboration over contract negotiation.**
	- **Responding to change over following a project plan**

- ==*What are the **principles behind LEAN** software development?*==
	- [[@poppendieckLeanSoftwareDevelopment2012#^fb4033]] [[@simangunsongLeanAgileSoftware2023#^52320e]]

## Misc

- ==*What are the properties of successful self organizationed teams?==*
	- According to https://www.youtube.com/watch?v=oRBMfO8DC0A
		- everyone holds each other accountable
		- clear norms and agreements 
		- having a coach 
		- bring whole self to work (are you psychologically safe)
	1. Autonomy: Team members have the freedom to make decisions and take action without constant oversight.
	2. . Clear Purpose: The team understands its goals and objectives clearly.
	3. Shared Leadership: Leadership responsibilities are distributed among team members rather than being centralized.
	4. Effective Communication: Open, transparent, and frequent communication fosters collaboration and coordination.
	5. Collaborative Decision-Making: Decisions are made collectively, with input from all team members.
	6. Continuous Learning and Improvement: The team embraces a culture of learning and regularly reflects on its processes to improve.
	7. Flexibility and Adaptability: The team can adjust its strategies and plans quickly in response to changes.
	8. Trust and Respect: Team members trust each other's abilities and treat each other with respect.
	9. Shared Accountability: Each team member shares responsibility for the team's performance and outcomes.
	10. Celebration of Diversity: The team values and leverages the diverse perspectives and skills of its members.
- ==*What is the purpose of a roadmap?==*
	- **It is important to have a baseline to work towards it**
	1. **Clarity of Direction**: It provides a clear direction and vision for the project, ensuring that all team members understand the goals, priorities, and timeline.
	
	2. **Alignment**: It aligns stakeholders and team members by communicating shared objectives and priorities, reducing misunderstandings and conflicts.
	
	3. **Resource Allocation**: It helps in allocating resources efficiently by identifying critical tasks, dependencies, and resource requirements, optimizing resource utilization throughout the project lifecycle.
	
	4. **Risk Management**: It allows for proactive identification and mitigation of risks by highlighting potential roadblocks, dependencies, and challenges ahead of time, enabling the team to develop contingency plans and strategies.
	
	5. **Communication and Transparency**: It facilitates communication and transparency among stakeholders by providing a common reference point for discussing project progress, priorities, and decisions.
	
	6. **Motivation and Engagement**: It fosters motivation and engagement among team members by illustrating progress, milestones achieved, and the impact of individual contributions, boosting morale and commitment to project success.
	
	7. **Adaptability**: It supports adaptability and flexibility by allowing for adjustments to the plan in response to changing requirements, stakeholder feedback, or unexpected events, ensuring the project remains responsive to evolving needs and circumstances.

---- 
## Summary of the different methodologies

## Royce
--- 
## SAFe (Example could be something like Google with their sollutions)
---
Scaled Agile Framework (SAFe) is an approach to scaling agile practices for large organizations. Here's a summary of the process in SAFe:

SAFe consists of three levels: Team, Program, and Portfolio.

1. **Team Level**: At the team level, Agile Teams consisting of 5-12 individuals work together to develop and deliver increments of value in short iterations, typically 2 weeks long. They use agile practices like Scrum or Kanban.

2. **Program Level**: The Program Level organizes teams into Agile Release Trains (ARTs), which align multiple teams around a shared mission or value stream. ARTs deliver value through a series of Program Increments (PIs), which are time-boxed iterations lasting 8-12 weeks. Each PI consists of planning, execution, and inspect and adapt events.

3. **Portfolio Level**: The Portfolio Level aligns business strategy and execution by organizing value streams, which represent the flow of value to the organization. Epics, large initiatives that span multiple PIs, are prioritized based on business objectives and the organization's strategy.

SAFe provides a set of roles, ceremonies, and artifacts to support this structure, including:
- **Roles**: Roles such as Product Owner, Scrum Master, Release Train Engineer, and Product Management provide clear accountabilities and responsibilities.
- **Ceremonies**: Ceremonies like PI Planning, System Demos, Inspect and Adapt, and Scrum of Scrums facilitate alignment, collaboration, and feedback at different levels.
- **Artifacts**: Artifacts like the Program Backlog, Program Board, Solution Intent, and Portfolio Backlog provide transparency and visibility into work items, priorities, and progress.

Overall, SAFe aims to help large organizations achieve agility by providing a structured approach to scaling agile practices across teams, programs, and portfolios while maintaining alignment with business objectives and strategy.

![[Pasted image 20240324103105.png]]
## Scrum
---

1. **Sprint Planning**: The Scrum team plans the work to be done during the sprint, selecting items from the product backlog to deliver by the end of the sprint.

2. **Daily Standup (Daily Scrum)**: The team meets daily for a brief stand-up meeting to discuss progress, challenges, and plans for the day. It's a time-boxed meeting lasting around 15 minutes.

3. **Sprint Execution**: Throughout the sprint, the team works on the selected backlog items, collaborating to develop and deliver increments of product functionality.

4. **Sprint Review**: At the end of the sprint, the team demonstrates the completed work to stakeholders and collects feedback. This meeting provides an opportunity to inspect the increment and adapt plans as needed.

5. **Sprint Retrospective**: Following the sprint review, the team holds a retrospective meeting to reflect on the sprint process, identify areas for improvement, and create actionable items for the next sprint.

6. **Backlog Refinement**: Throughout the sprint, the team engages in backlog refinement activities to clarify requirements, estimate effort, and prioritize backlog items for future sprints.

## Scrum of Scrums
---
Scrum of Scrums (SoS) is a technique used in Scrum, an agile framework for managing and developing complex products. It's designed to coordinate work among multiple Scrum teams, especially in larger projects where a single Scrum team may not be sufficient. 

**Process:**

1. **Formation of Scrum of Scrums:** When multiple Scrum teams are working on interrelated components or a larger project, representatives from each team form a Scrum of Scrums group. These representatives are often Scrum Masters or team leads.

2. **Regular Meetings:** The Scrum of Scrums group holds regular meetings, typically daily or several times a week, to discuss progress, dependencies, and any impediments or blockers that affect the overall project.

3. **Information Sharing:** During the meetings, each team representative provides updates on their team's progress, including what they've accomplished, what they plan to do next, and any obstacles they're facing.

4. **Issue Resolution:** The Scrum of Scrums group collaboratively identifies and addresses any dependencies or issues that arise between teams. They work together to find solutions and ensure that work progresses smoothly across all teams.

5. **Backlog Coordination:** The group may also coordinate the product backlog items or user stories across teams to ensure alignment with the overall project goals and priorities.

**Practices:**

1. **Rotation:** To ensure equal participation and representation from all teams, the role of attending the Scrum of Scrums meeting may rotate among team members or designated representatives.

2. **Shared Information:** Teams share relevant information such as sprint goals, progress metrics, impediments, and dependencies during the Scrum of Scrums meetings to maintain transparency and alignment.

3. **Action Items:** The Scrum of Scrums group may identify action items or follow-up tasks to address specific issues or dependencies between teams. These action items are tracked and monitored until resolved.

**Advantages:**

1. **Improved Coordination:** Scrum of Scrums facilitates better coordination and communication among multiple teams working on a shared project, reducing duplication of effort and ensuring alignment towards common goals.

2. **Early Issue Identification:** By sharing updates and discussing dependencies regularly, teams can identify potential issues or conflicts early and address them before they escalate into major problems.

3. **Faster Problem Resolution:** The collaborative nature of Scrum of Scrums allows teams to work together to resolve dependencies or impediments more quickly, enabling smoother progress and delivery of work.

**Disadvantages:**

1. **Time Constraints:** Holding regular Scrum of Scrums meetings can be time-consuming, especially if there are many teams involved. Teams may find it challenging to balance the time spent in meetings with actual development work.

2. **Limited Scope:** Scrum of Scrums may not address all the challenges associated with large-scale projects, such as coordination with non-agile teams or external stakeholders. Additional coordination mechanisms may be needed.

3. **Dependency Management:** While Scrum of Scrums helps identify and address dependencies between teams, it may not fully eliminate the risks associated with complex interdependencies, especially in highly integrated systems.

Overall, Scrum of Scrums is a valuable practice for coordinating work among multiple Scrum teams, but it's important to adapt and tailor the approach to suit the specific needs and dynamics of the project and organization.
## Lean
---
- Lean summary
	- Lean methodology is a systematic approach to identifying and eliminating waste within a process to improve efficiency and create more value for customers. Originally developed by Toyota in the 1950s, Lean has since been applied across various industries and sectors. Here's a summary of its key principles and techniques:

	1. **Value:** Focus on delivering value to the customer by understanding their needs and preferences. Value is defined as any action or process that directly contributes to meeting customer requirements.
	2. **Value Stream:** Map out the entire value stream, including all the activities required to deliver a product or service to the customer. Identify both value-adding and non-value-adding activities to streamline the process and eliminate waste.
	3. **Flow:** Create a smooth and continuous flow of work through the value stream by reducing batch sizes, minimizing waiting times, and optimizing production or service delivery processes.
	4. **Pull:* (JIT)* Implement a pull-based system where work is initiated in response to customer demand, rather than pushing work through the system based on forecasts or schedules. This helps prevent overproduction and excess inventory.
	5. **Perfection:** Strive for continuous improvement and perfection by constantly seeking ways to eliminate waste, reduce variability, and improve processes. Encourage a culture of experimentation, problem-solving, and learning.
	6. **Respect for People:** Value and empower employees by involving them in the improvement process, providing training and support, and recognizing their contributions. Foster a culture of mutual respect, collaboration, and trust.

	- Lean methodology provides a framework for organizations to optimize their processes, reduce costs, improve quality, and enhance customer satisfaction. By focusing on value creation, waste elimination, and continuous improvement, Lean helps organizations become more agile, responsive, and competitive in today's dynamic business environment.
- What is a value stream in Lean
		- In Lean methodology, a value stream refers to all the activities (both value-adding and non-value-adding) required to deliver a product or service to a customer. It encompasses the entire process from the initial request or order from the customer to the delivery of the final product or service. The goal of analyzing and optimizing the value stream is to identify and eliminate any wasteful activities (often referred to as "muda" in Lean) and streamline the process to maximize efficiency and value for the customer.A value stream typically consists of three main types of activities:

	1. **Value-Adding Activities:** These are activities that directly contribute to meeting the customer's needs or requirements. Examples include designing, manufacturing, assembling, and testing components of a product, as well as providing specific services requested by the customer.
	2. **Non-Value-Adding Activities (Waste):** These are activities that do not add value to the product or service and should ideally be eliminated or minimized. Examples include waiting, unnecessary transportation, excessive inventory, overproduction, rework, and unnecessary processing steps.
	3. **Value-Enabling Activities:** These are activities that, while not directly adding value to the product or service, are necessary to support the value-adding activities. Examples include quality assurance, maintenance, setup/changeover, and training.

By mapping out the entire value stream and identifying areas of waste, organizations can implement Lean principles and techniques to streamline processes, reduce lead times, improve quality, and ultimately deliver greater value to customers while minimizing costs and resources.
- What are principles of lean software development
	- 1. **Eliminate waste****.** After each [development iteration](https://www.techtarget.com/searchsoftwarequality/definition/iterative-development), project managers discuss bottlenecks, identify waste and develop a plan to eliminate it. The Lean philosophy has a broad definition of waste that includes anything that doesn't add value to the product. Some examples are the following:
    - unnecessary code or software features;
    - more tasks than can be completed in the task log;
    - bureaucratic processes; and
    - quality issues.
	1. **Build in quality****.** Various tactics are used to ensure quality is built into the Lean process, such as [pair programming](https://www.techtarget.com/searchsoftwarequality/definition/Pair-programming) and [test-driven development](https://www.techtarget.com/searchsoftwarequality/definition/test-driven-development).
	2. **Amplify learning****.** Knowledge one software engineer gains must be shared with every engineer on the software development team. This occurs through code review and sharing at meetings. Also, engineers learn as they go and question assumptions.
	3. **Delay commitment as long as possible****.** The goal is to experiment and learn as much as possible before committing to irreversible decisions. Developers incorporate features and functionality as late as possible in the process to prevent having to redo work as the market changes.
	4. **Deliver fast****.** Developers launch a product quickly, receive customer feedback fast and use that feedback to create a strategy for improvement. The idea behind this approach is to [fail fast](https://www.techtarget.com/whatis/definition/fail-fast) and learn from the results. This strategy contrasts with other methodologies used to design complex products. They often take a lot of time and still end up failing.
	5. **Respect people****.** Respect is the basis for a productive, collaborative atmosphere. Lean encourages healthy conflict, proactive communication and constant feedback.
	6. **Optimize the whole****.** The team examines the process from start to finish to [make the Lean value stream as efficient as possible](https://www.techtarget.com/searchsoftwarequality/tip/How-Lean-value-stream-mapping-cuts-delay-boosts-efficiency). It contrasts with the concept of suboptimization, where subpar code is generated faster than it can be tested for the sake of speed and software testers are overloaded.
- Challenges for Software Development
	- **Team training requirements.** If a team is unable to work together and communicate, development efforts suffer. Teams and team members must be trained so they can take on each other's work and adapt to changing initiatives. They must also be able to organize work and trade duties as priorities change.
	- **Missing metrics.** A common pitfall of Lean is measuring the wrong [software metrics](https://www.techtarget.com/searchsoftwarequality/tip/23-software-development-metrics-to-track-today) or not measuring at all. Since one of the main goals of Lean software engineering is to eliminate waste, teams must be able to identify waste and measure it.
	- **No boundaries.** [Software requirements specifications](https://www.techtarget.com/searchsoftwarequality/definition/software-requirements-specification) evolve in Lean as customers provide feedback. Too many requirements and too much change create complexity and make it difficult to release a cohesive piece of software.
	- **Suboptimization.** Suboptimization is when only part of the production system's [value stream](https://www.techtarget.com/searcherp/definition/value-stream-mapping) is optimized. This happens when a problem is broken into parts that are solved in isolation without considering the effect one part will have on other parts or the entire system.
## Less
---

**Large-Scale Scrum (LeSS)** is an agile framework for scaling Scrum to multiple teams working on a single product. 

**Overview:**

1. **Simplicity:** LeSS is based on the principles of Scrum, emphasizing simplicity and lightweight processes. It avoids adding unnecessary complexity and layers of hierarchy, focusing on the essentials of agile development.

2. **Single Product Focus:** Unlike other scaling frameworks that may involve multiple products or projects, LeSS focuses on a single product or product line. This ensures alignment, shared understanding, and a clear product vision across all teams.

3. **Team Autonomy:** LeSS promotes self-managing, cross-functional teams. Each team is responsible for end-to-end delivery of potentially shippable increments of the product, fostering ownership, collaboration, and accountability.

4. **Transparency:** LeSS emphasizes transparency at all levels of the organization. Teams have access to relevant information, such as product backlog, sprint goals, and metrics, enabling informed decision-making and alignment with the overall product vision.

**Advantages:**

1. **Simplicity and Flexibility:** LeSS provides a lightweight framework that is easy to understand and implement. It allows organizations to scale agile practices without introducing unnecessary complexity or bureaucracy.

2. **Improved Product Quality:** By focusing on a single product and encouraging cross-functional teams, LeSS promotes collaboration, shared understanding, and collective ownership, leading to higher product quality and customer satisfaction.

3. **Enhanced Communication and Collaboration:** LeSS fosters communication and collaboration among teams, stakeholders, and customers. Regular ceremonies, such as Sprint Reviews and Product Backlog Refinement, provide opportunities for feedback and alignment.

4. **Adaptability:** LeSS encourages empirical process control and continuous improvement. Teams inspect and adapt their processes based on feedback and data, enabling them to respond quickly to changes in the market or customer needs.

**Disadvantages:**

1. **Challenges in Large Organizations:** While LeSS is designed to scale agile practices, it may face challenges in very large organizations with complex structures, dependencies, and legacy processes. Adapting existing organizational structures and culture to LeSS may require significant effort and change management.

2. **Resource Constraints:** LeSS relies on having sufficient resources, such as skilled practitioners, to form and sustain cross-functional teams. In organizations with resource constraints or competing priorities, implementing LeSS may be challenging.

3. **Coordination Overhead:** Although LeSS promotes self-managing teams, there may still be a need for coordination and alignment across multiple teams. Managing dependencies, communication, and integration between teams can introduce overhead and complexity.

4. **Training and Adoption:** Successfully implementing LeSS requires training, coaching, and support for teams and stakeholders. Organizations may face challenges in providing adequate training and ensuring consistent adoption of LeSS practices across teams.

In summary, LeSS offers a simple, flexible, and focused approach to scaling Scrum for large product development efforts. While it provides numerous benefits, such as improved product quality and collaboration, organizations should carefully consider the challenges and requirements associated with adopting LeSS in their context.
## Spotify Model
--- 
![[Pasted image 20240324103319.png]]
## Difference between SoS and SAFe
---

1. **Scope:**
   - **Scrum of Scrums (SoS):** SoS focuses specifically on coordinating work among multiple Scrum teams. It is a lightweight approach that typically involves representatives from each team meeting regularly to discuss progress, dependencies, and issues.
   - **Scaled Agile Framework (SAFe):** SAFe is a comprehensive framework that provides guidance on organizing, planning, and executing agile projects at scale. It encompasses not only multiple Scrum teams but also other agile practices, roles, and artifacts to address the needs of large and complex organizations.

2. **Structure:**
   - **Scrum of Scrums (SoS):** SoS is more informal and decentralized in structure. It relies on regular meetings and communication between representatives from each team to coordinate work and address dependencies.
   - **Scaled Agile Framework (SAFe):** SAFe provides a structured framework with defined roles, ceremonies, and artifacts at different levels of the organization, including teams, programs, and portfolios. It introduces additional layers of coordination and alignment to ensure consistency and synchronization across teams.

3. **Roles and Responsibilities:**
   - **Scrum of Scrums (SoS):** SoS typically involves representatives from each team, often Scrum Masters or team leads, who are responsible for sharing updates, identifying dependencies, and resolving issues.
   - **Scaled Agile Framework (SAFe):** SAFe defines specific roles at different levels of the organization, such as Agile Teams, Release Trains, Solution Trains, and Portfolio. Each role has distinct responsibilities for planning, execution, and coordination within the framework.

4. **Scaling Approach:**
   - **Scrum of Scrums (SoS):** SoS is primarily focused on scaling Scrum practices to coordinate work among multiple teams. It relies on principles of transparency, inspection, and adaptation to manage dependencies and ensure alignment.
   - **Scaled Agile Framework (SAFe):** SAFe takes a more comprehensive approach to scaling agile practices beyond Scrum. It incorporates principles from Lean and DevOps and provides guidance on scaling agile across teams, programs, and the entire enterprise.

In summary, while both Scrum of Scrums and Scaled Agile Framework aim to address the challenges of scaling agile practices in large organizations, they differ in scope, structure, roles, and scaling approach. Scrum of Scrums is a simpler, team-level coordination mechanism within the Scrum framework, while SAFe provides a more structured and comprehensive framework for scaling agile practices across the organization.