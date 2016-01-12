
Reflective Report

Selected articles: 

1.	Gorschek & Wohlin “Requirements Abstraction Model”

2.	Khurum & Gorschek “A method for early requirements triage and selection utilizing product strategies”

I have found Requirements Abstraction Model and A Method for Early Requirements Triage and selection Utilizing Product Strategies to be more interesting and the methods discussed in the articles to be more accessible for implementation and execution.

Implementation:

Placement of the requirements into four abstraction levels from “requirements abstraction model”.

Identifying the importance of the requirements from “A Method for Early Requirements Triage and selection Utilizing Product Strategies”.

Execution:

1.	Placement of requirements into four abstraction levels.

I have selected online application store as the system. Some of the requirements are identified and placed into four abstraction levels. Most of the identified requirements will be from my experience with the release planning and my previous projects.

2.	Identifying priority of requirements by assigning weights. 

Proof of Concept:

1.	Placement of requirements into four abstraction levels.

Step 1 Specify

RQ1: Signup page

Description: The customer should be able to create an account in the sign up page.

Reason/Benefit/Rationale: The user wants to maintain private profile of his banking details and purchases.

BENEFIT: The user can use this to do purchases which are accessible only through this account.

Restrictions/Risks: Only one account can be created with one email.

RQ2: Homepage

Description: The system should be able to display the categories and popular application details in the home page.

Reason/Benefit/Rationale: To display available categories of the applications  

BENEFIT: Easy browsing of the available categories.

Restrictions/Risks: Only one category can be selected from different categories.

RQ 3: Selected category page

Description: The system should be able to display applications in the selected category

Reason/Benefit/Rationale: finding the application for which customers are looking to purchase/download. 

BENEFIT: Finding the application will be simpler.

Restrictions/Risks: Applications are displayed based on popularity so there is chance of customer not finding the application he is looking for in the initially displayed page.

RQ 4 Check-out

Description: The system should be able to check out the customers and take them to the payment gateway.

Reason/Benefit/Rationale: For concluding the purchase. 

BENEFIT: The customer can finish the purchase and immediately start downloading the application.


RQ 5 Adding applications into cart

Description: The customer should be able to add/remove applications from the cart for purchase.

Reason/Benefit/Rationale: For easy checkout and payment.

Restrictions/Risks: limits the feature only to the customers who have logged in through their account.

RQ 6 Payment gateway

Description: The customers should be able to purchase the applications through payment gateway

Reason/Benefit/Rationale: To perform secured transaction with debit/credit cards. 

BENEFIT: Having a payment gateway will increase security of wireless transactions.

Restrictions/Risks: Might consume more time of the customer.

RQ 7 Products database

Description: Database is required to maintain the application files and to store user credentials.

Reason/Benefit/Rationale: The customer should be able to download the application through the internet. 

BENEFIT: Provides access to applications immediately after purchase.

Restrictions/Risks: Frequent maintenance might be required.

Step 2 Place

After specifying the requirements, they can be placed into four different abstraction levels.

Product level: Product database, payment gateway
Feature level: Adding into the cart
Function level: signup page, homepage, checkout
Component level: selected category page

Homepage requirement into component level: Popular deals page and purchase history  

RQ 8 Popular deals page

Description: The system should be able to display popular deals.

Reason/Benefit/Rationale: The customer might want to know and purchase the popular applications.

Restrictions/Risks: only high rated applications will be shown.

RQ 9 Purchase history  

Description: Displays the purchase history of the customer.

Reason/Benefit/Rationale:  To list out the applications he has purchased so far. 

BENEFIT: Details of the purchases are available.

Restrictions/Risks: Purchases are ordered from recent to old purchases.

Payment gateway into functional level requirement: Mobile bankid

RQ 11 Mobile bankid option

Description: Purchase can be made through mobile bankid.

Reason/Benefit/Rationale:  Payments can be made through mobile phones 

BENEFIT: Secured transactions can be made by customer.

Restrictions/Risks: Connectivity problems might occur as the authorizing device is mobile phone.

Step 3 Abstraction (work up)

This third step of RAM involves abstracting and/or breakdown of a requirement, depending on the initial placement of the original requirement. The work-up process involves creating new requirements (called work-up requirements hereafter) on adjacent abstraction levels or linking to already existing ones, depending on the situation. Next step is to prioritize the requirements. 

2.	A Method for Early Requirements Triage and selection Utilizing Product Strategies

In order to explicitly state the goals and objectives of a product, it is important to specify the directions of movement for the product deduced from the organization’s mission statement. Thus it is important to answer the three strategic questions Where we want to go?, (2) How to get there?, (3) What will be done?) for each product. The output of this step is an explicit understanding of goals and objectives associated with a specific product which can be used to perform requirements triage and selection for individual products. As the system is targeted for customers who are more inclined towards purchasing popular applications, Popular deals page requirement is selected for method 

Where we want to go? Can be answered by assigning weights to the Profit(40), Growth(30), Market share(30)

How to get there? Can be answered by assigning weights to the European market (20), American market (60), and Asian market (20) 

What will be done? Can be answered by assigning weights to the Application promotion (60), distribution (20), Service (20)

The normalization of the data is done and the popular deals page requirement is prioritized by the comparing normalization values of other requirements.

Lessons Learned:

I was unable to execute the method as discussed in the articles because most of the requirements considered for the system are of basic level. After the execution of the methods I have found that more research on requirement prioritization techniques is required.

Reflections:

Through my experience with the method in article 1, I have implemented the RAM method which is to abstract, break down the requirements as needed and offering requirements on several levels of abstraction reflecting my requirements of the project. 

Through my experience with the method in article 2, I have implemented the method and dealt with the requirements continuously, performing early triage of requirements, selecting the ones aligned with a specific product’s strategy. Inappropriate requirements are not considered to avoid expending resources for the triage activity as the process has to handle other requirements.

