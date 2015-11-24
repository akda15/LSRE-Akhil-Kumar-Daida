SEMINAR 0
1.	What is large scale requirements engineering?
2.	What are the challenges in large scale requirements engineering?
3.	What is the order of magnitude of the number of requirements we are discussing?
4.	Read up on and summarize [Strategic] Release Planning
	
1.	Large Scale Requirements Engineering:
Requirements engineering addresses the critical problem of designing the right software for the customer. The complexity and size of software intense systems continues to grow, which in turn gives increasingly large and complex sets of requirements. As a result, the size and complexity of the requirements databases grow even faster than the size and complexity of actual software products. This situation is named Large-Scale Requirements Engineering (LSRE).
Large companies often manage thousands of requirements continuously arriving from multiple sources. These requirements are often inter-related and originate from an increasing number of customers, end users, developers, subcontractors, product features, and external system interfaces. This context is defined as very large-scale RE (VLSRE).

Article: “Visualizing, Analyzing and Managing the Scope of Software Releases in Large-Scale Requirements Engineering”

2.	Challenges of LSRE:
• Large number of customer requirements: A large number of customer requirements posed challenges for analyzing, specifying, and managing requirements.
• Formal interface to customer: Communication with the customer will be formal, meaning that official submittal and review processes had to be followed on most issues. This level of formality greatly increased the time required to receive feedback and clarifications from the customer.
• Management of customer expectations: Since it will be a large and complex system, early prototypes of the system will be shown to the customer, expectations of the customer on how far development had already progressed needed to be properly managed.
• Traceability: Full bi-directional traceability is required for all development artifacts, including requirements. Creating and maintaining the traces will be a difficult task, due to the amount of time and manual effort required.
• Scope change and creep: Scope change and creep is natural and unavoidable in large projects. For instance, due to changes in technologies and processes, the customer requested modifications to some of their requirements. Accommodating the change in scope while still meeting the project milestones will be demanding.

Article: “Requirements Engineering in the Development of Large-Scale Systems”

3.	Order of magnitude of requirements:
Abbrev	level	Order of magnitude
SSRE	  Small Scale Requirements engineering	10 requirements
MSRE	  Medium Scale Requirements Engineering	100 
        requirements
LSRE	  Large Scale Requirements Engineering 	1000 requirements
VLSRE	  Very Large Scale Requirements Engineering	10000 requirements

Article: “Can We Beat the Complexity of Very Large-Scale Requirements Engineering?”

4.	Release Planning:
Release planning could be described as selecting an optimal subset of requirements for realization in a certain release. Release planning is where requirements engineering for market-driven software product development meets the market perspective. It determines which customer gets what features and quality at what point in time. The selection task is normally preceded by requirements prioritization, which has received increasing interest in recent years [1, 2], and resource estimation, which has been an issue within software engineering since its origins. Once this is done it may seem to be a fairly straightforward task to select requirements from the priority list until the total estimate equals the available resources.

Article: “Release Planning in Market-Driven Software Product Development: Provoking an Understanding”

SUMMARY OF ARTICLES:

-Article discusses about two approaches of release planning, one is the art of release planning and other the science of release planning. The art of planning requires the human intuition and capabilities to clarify a problem before seeking a solution. The Science of release planning will formalize the plan by setting up importance criteria for customers in an organization and satisfying the requirements according to the importance of customers. This can be done identifying features, dependencies between features and feature prioritization by calculating their value and risk.
Article also discusses about objective function and hybrid approach based on integer linear programming.
The planning objective is typically a mixture of different aspects such as value, urgency, risk, satisfaction or dissatisfaction, and return on investment. Few assumptions were made in the model
1.	An additive function exists in which the total objective function value is determined as the sum of the weighted average satisfaction WAS (i, k) of stakeholder priorities for all features f(i) when assigned to release k. 
2.	Each value WAS (i, k) is determined as the weighted average of the products of the two dimensions. 
3.	Stakeholder S(p)’s degree of impact is determined by the relative importance.   
4.	For each release option k, normalized parameters describe each option’s relative importance.
5.	A vector of urgency preference for each stakeholder and each feature, given as urgency (p, i) = (urgency (p, i, 1), urgency (p, i, 2), urgency (p, i, 3)).
Hybrid approach offers a high-level framework stressing the continuous process needed to perform planning and re-planning. There are 3 phases in the planning process to improve hybrid approach.
1.	Modeling: Plan objectives and constraints, Offer stakeholder voting and estimate resources are activities of modeling phase
2.	Exploration: Solution will be generated based on the formal model
3.	Consolidation: Decision maker evaluates the computational algorithm’s solution alternatives based on experience and the problem context. This helps the decision maker better understand the problem.

Article: “The art and science of release planning”

-Article discusses about QUPER model and need of using this model to identify quality requirements while release planning. Quality requirements can be elicited by 
1.	Identifying candidate quality requirements: Quality requirements can be identified by considering relevant features, market segment, competitor and hardware platform capability
2.	Defining scale and unit
3.	Identify reference levels: Identifying reference levels based on actual products. Reference levels can be based on competing as well as own products.
4.	Elicit quality breakpoints: Determining the utility breakpoint which is the lowest acceptable value on the market for a given segment.
5.	Estimate cost barriers: For estimating cost barriers, practitioners with good domain and architectural knowledge are required.
6.	Set candidate requirements: Deciding which requirements for the next releases.
7.	Identify cost dependencies: For improvements of existing quality requirements, costs are estimated.
Case study was conducted to evaluate QUPER model. Two evaluations of the complete QUPER model was carried out using a qualitative research approach, namely in-depth semi-structured interviews and self-administrated questionnaires. Results of case study show that that the QUPER model is easy to understand and the model does not take too much time to apply in practice.

Article: R: Berntsson Svensson, B. Regnell (2015) “A case study evaluation of the guideline-supported QUPER model for elicitation of quality requirements”, 21st International Working Conference on Requirements Engineering: Foundation for Software Quality (REFSQ’15), Essen, Germany, pp. 230-246, 2015.

-Article discusses about QUPER tailoring implementation and most important evaluation conducted at Sony Ericsson, one of the leading mobile handset developers. QUPER is validated for its usefulness in a non-simulated environment in real projects using real requirements. Development of QUPER was carried out at two case companies in the mobile handset domain with a supplier-integrator relationship. Development steps of QUPER includes: 
1.	Problem definition: Different requirement decision scenarios were identified by focusing on the interface between two case companies
2.	Model definition: QUPER model defined comprising three views a benefit view, a cost view, a roadmap view.
3.	Model validation: An evaluation of the model was carried out in six cases of selected subdomains through interviews with experts.
Evaluation of QUPER only include QUPER benefit view because it was considered most important part of the QUPER model for Sony Ericsson to start with. Four steps were detailed on how to use the QUPER benefit view.
1.	Defining quality aspects
2.	Estimating product’s current quality
3.	Estimating breakpoints for each quality aspect and for each relevant qualifier
4.	Estimating candidate targets and deciding on actual targets for next releases
Case study was done through 3 steps 
1.	Interview (Part 1): Brainstorming and planning meeting were performed to plan the study and identify different areas of interests for evaluation. The interview instrument was designed with respect to different areas of interest.
2.	Workshop: QUPER and how to use QUPER in practice was presented in a workshop. During the workshop, a selection of requirement engineers and managers (including the subjects that participated in interview – part 1) were present. These representatives were selected based on their roles and expertise by the local managers. As they were invited, they were asked to prepare for the workshop by reading requirements from their real projects. In total, six workshops were conducted at different geographical locations and varied between 60 and 90 minutes in length. During the workshop, the author provided help and feedback to the subjects about applying QUPER on their requirements.
3.	Interview (Part 2): Interviews were carried out by author.
Evaluation results from the case study were:  All areas, except email, had specified performance requirements. A general tendency observed is that performance requirements were indirectly controlled by standards or hardware components and/or suppliers. There are three main reasons why the email area did not have any performance requirements: (1) performance was continuously tested by the testing department, (2) the operating system supplier performed performance testing, and (3) no structured process of how to handle performance requirements existed. However, internal performance requirements are now introduced in the email area. One reason is the introduction of the QUPER model, which provides a structured process of handling performance requirements, and more control over the requirements in terms of understanding why a particular quality level is needed and the relation to the competitors. In general, the areas handled performance requirements in two ways: (1) looked at different standards stated performance and (2) the performance was provided by either hardware suppliers or the market department. Those quality levels were accepted without an understanding of why they were important.
The conducted evaluation shows that QUPER is easy to understand and learn, straight forward, and not complicated to apply in Sony Ericsson’s current practice. In fact, all subjects stated that they are and will use QUPER. In addition, the concepts behind QUPER improve the communication among staff regarding requirements prioritization. The main identified challenge was difficulties to identify and specify the values for the differentiation and saturation breakpoints.

Article: Berntsson Svensson & Olsson “Introducing support for release planning of quality requirements –an industrial evaluation of the QUPER model”

-Article describes a specific industrial Requirements Engineering (RE) process for packaged software, called REPEAT (Requirements Engineering Process At Telelogic), which is enacted by the Swedish CASE-tool vendor Telelogic AB - a fast growing company, currently with 180 employees, more than 600 customers worldwide, and a predicted revenue for 1998 of circa 200 million SEK (increase from 107 million SEK, 1997). REPEAT is used in-house at Telelogic for eliciting, selecting and managing requirements on a product family called Telelogic Tau - a software development environment for real-time systems, used by many of the world's largest telecommunication systems providers in their software development. Telelogic Tau supports standardized graphical languages, such as SDL [1], MSC [2], TTCN [3], and UML [4], and provides code generators for integration with several real-time operating systems) Telelogic Tan is an integration of in-house developed COTS components and can be tailored for the specific needs of a customer or a market segment, and is available on UNIX and Microsoft Windows platforms. It is built using an architecture with an implicit invocation style, which enables changes with local impact.
REPEAT is an RE process that manages requirements throughout a whole release cycle. It covers typical RE activities, such as elicitation, documentation, and validation, and has a strong focus on requirements selection and release planning. Management of requirements changes due to new market demands.
Actors involved in REPEAT include:
1.	Requirements management group
2.	Issuer: Any employee at Telelogic can submit a requirement to Requirements management group. An issuer is usually a person from marketing and sales or customer support, but can also be a developer or a tester
3.	Customers and users provide input and feedback to an issuer regarding user and market demands
4.	Requirements team
5.	Construction team
6.	Test team
7.	Expert
8.	Requirements database
The requirements management group with support from experts is responsible for deciding on requirement state transitions
1.	New
2.	Assigned
3.	Classified
4.	Rejected
5.	Selected
The elicitation phase includes two activities: collection and classification. Collection of requirements is made by an issuer that fills in a web form and submits the requirement for storage in Requirements database. Requirements are described using natural language and given a summary name by the issuer. An explanation of why the requirement is needed is also given. The issuer gives the requirement an initial priority P, which suggests in which release it may be implemented.
The goals of Selection phase are: (1) to select which requirements to implement in the current release; (2) to specify the selected requirements in more detail; and (3) to validate the requirements document. The output of this phase is a requirements document (RD) which includes a selected list, a detailed specification of all selected requirements, and a not selected list including the requirements that are postponed to the next release.
After specification baseline, the REPEAT process instance enters the change management phase. When this happens, a new REPEAT process instance is started in the elicitation phase. During change management, the Requirements management Group takes decisions on changing the RD caused by new incoming requirements with P = 1, i.e. high-priority requirements that are suggested to impact the current development process (including construction and verification) running in conjunction with the change management phase of REPEAT.
The major elements of REPEAT-1 that were believed to cause the dramatic improvements in release precision and product quality are the prioritization of requirements, the effort estimation, the detailed requirements specification, and the continuous change management throughout design, implementation and verification. The classification activity gives experts the opportunity to carefully consider which requirements to implement in which release, so that the requirements that are believed to give the highest value to the lowest cost are implemented first. The must- and wish-lists are strong tools for enforcing that a release project does not take in more requirements than can be achieved within six months. Customer support and marketing can easily issue requirements as a reaction to their observation of end-user and market needs.

Article: Regnell et al. “A market-driven requirements engineering process: results from an industrial process improvement programme”

