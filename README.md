# requirement-analysis

# Requirement Analysis in Software Development

This repository serves as a dedicated platform for documenting and overseeing the requirements essential for our software development endeavors. Its principal objective is to establish a comprehensive and centralized repository that guarantees a shared comprehension of the project's demands among all involved parties.



# Purpose of the Repository:

- Centralized Documentation: Acts as a singular, well-structured repository for all requirement-related materials, encompassing user stories, use cases, and functional and non-functional requirements.

- Collaboration: Encourages teamwork and engagement among team members, stakeholders, and clients by fostering discussions, receiving feedback, and providing updates on requirements.

- Traceability: Ensures meticulous tracking of requirements throughout the development cycle, aiding in change management and preserving a transparent record of decisions.

- Quality Assurance: Serves as the foundation for validating that the final product fulfills all specified requirements, thereby guaranteeing high quality and user satisfaction.

- Project Management: Aids in project planning and progress monitoring by precisely defining and prioritizing requirements.

This repository plays a crucial role in promoting transparency, collaboration, and quality assurance throughout the software development process. It acts as a central hub for requirement-related information, facilitating effective communication and decision-making among project stakeholders.





# What is Requirement Analysis

Requirement Analysis, also known as requirements engineering, is a crucial phase in the software development lifecycle (SDLC). It involves identifying, documenting, and managing the needs and requirements of stakeholders to ensure the successful delivery of a software product. This process helps translate business needs into detailed software requirements, guiding the design and development phases.



# Key Activities in Requirement Analysis

Requirement Elicitation: Gathering requirements from stakeholders through techniques like interviews, surveys, workshops, and observation. The goal is to understand what the stakeholders need from the software.

Requirement Documentation: Creating detailed documents that outline the requirements. This may include use cases, user stories, and functional and non-functional requirements.

Requirement Analysis: Evaluating the gathered requirements to ensure they are clear, complete, consistent, and feasible. This step involves prioritizing requirements based on their importance and impact.

Requirement Specification: Compiling the requirements into a formal document, often referred to as the Software Requirements Specification (SRS), which serves as a reference throughout the development process.

Requirement Verification and Validation: Ensuring that the documented requirements meet stakeholder needs and that the final product fulfills these requirements.

Requirement Management: Tracking and managing changes to requirements throughout the project lifecycle to ensure they remain aligned with stakeholder needs and project goals.



# Importance of Requirement Analysis in SDLC

- Clarity and Understanding: Requirement Analysis helps in gaining a clear understanding of what the stakeholders want. This clarity is essential for developing software that meets their needs and expectations.

- Scope Definition: Clearly defined requirements help in defining the scope of the project, preventing scope creep and ensuring that the project stays on track.

- Foundation for Design and Development: Well-documented requirements provide a solid foundation for the design and development phases. They guide developers and designers in creating a product that aligns with stakeholder expectations.

- Improved Communication: Requirement Analysis fosters better communication between stakeholders and the development team. It ensures that everyone is on the same page, reducing misunderstandings and misinterpretations.

- Risk Management: Identifying and analyzing requirements early in the SDLC helps in identifying potential risks. This enables the team to plan for risk mitigation, reducing the likelihood of project delays and cost overruns.

- Quality Assurance: Requirements serve as a benchmark for testing and validation. They ensure that the final product meets the specified criteria and delivers the expected functionality and performance.

- Cost and Time Efficiency: Well-defined requirements help in estimating project costs and timelines more accurately. They reduce the likelihood of rework and scope changes, saving time and resources.

- Customer Satisfaction: Meeting stakeholder needs and expectations through a thorough Requirement Analysis process leads to higher customer satisfaction. It ensures that the delivered product adds value and addresses the intended problems.




# Why is Requirement Analysis Important?

# Clarity and Precision

Description: Requirement Analysis ensures that all stakeholders have a clear and precise understanding of what the software needs to achieve.

Importance: This clarity helps prevent misunderstandings and miscommunications, which can lead to costly errors and rework. It ensures that everyone involved in the project is on the same page and working towards the same goals.

# Scope Definition

Description: Defining the scope of the project through detailed requirements helps identify the boundaries and limitations of what the software will deliver.

Importance: This prevents scope creep, where additional features or changes are added without proper planning, which can derail the project. Clear scope definition helps keep the project focused and manageable, ensuring that it stays on track and within budget.

# Risk Management

Description: Identifying and analyzing requirements early in the SDLC helps in recognizing potential risks and planning for their mitigation.

Importance: By addressing risks upfront, the development team can devise strategies to minimize their impact, reducing the likelihood of project delays, cost overruns, and failures. Proactive risk management ensures a smoother development process and a higher chance of project success.


# Key Activities in Requirement Analysis

# Requirement Gathering

- Involves collecting comprehensive information about stakeholders' needs for the software product, defining desired functionality and constraints.

- Foundation of requirement analysis, ensuring a clear understanding for building a product that meets stakeholder expectations.


# Requirement Elicitation

- Extracting requirements from stakeholders using techniques like interviews, surveys, workshops, and observation to uncover real needs and expectations.

- Identifying all relevant requirements, including implicit ones, for a more complete set of requirements.


# Requirement Documentation

- Creating detailed documents capturing gathered and elicited requirements, including use cases, user stories, and Software Requirements Specifications (SRS).

- Serves as a reference for the development team, ensuring consistent understanding and preventing misunderstandings.


# Requirement Analysis and Modeling

- Analyzing requirements for feasibility, consistency, and completeness. Using modeling techniques like data flow diagrams and use case diagrams for visual representation.

- Identifying gaps or conflicts in requirements, providing clear visual representation for communication and validation.


# Requirement Validation

- Ensuring documented requirements reflect stakeholder needs and that the product will meet these requirements. Techniques like reviews and prototyping are used.

- Validates correctness, completeness, and feasibility of requirements, detecting errors early to reduce costly changes later.






# Types of Requirements.

https://drive.google.com/file/d/1fv_CM-A_OajzlJWNq-6dlUhrUjvtvmoo/view?usp=drive_link

 # Hotel Management Service


# Functional Requirements:

- Hotel Information Management:

Ability for hotel managers to add, update, and delete hotel information (e.g., room types, prices, availability).

Example: A manager updates the room rates for a peak season.

- API Handling:

APIs to handle requests for hotel data.

Example: An API call to update the number of available rooms.

- Load Balancing:

Distribute incoming requests across multiple servers.

Example: Requests from hotel manager apps are distributed to different servers to balance the load.

Data Sync with CDN and Messaging Queue:

Sync updates to CDN and messaging queues for further processing.

Example: A room availability update is sent to the CDN and RabbitMQ.


# Non-functional Requirements:

- Performance:

The system must handle high volumes of requests efficiently.

Example: The load balancer can handle thousands of requests per second.

- Scalability:

The ability to scale horizontally by adding more servers.

Example: Adding more servers to the hotel service cluster during peak seasons.

- Reliability:

Ensures the system is available and operational 99.99% of the time.

Example: Using a failover mechanism in case one server goes down.

- Security:

Secure data transmission and storage.

Example: Using SSL/TLS for secure communication and encryption for sensitive data.



# Customer Service (Search + Booking)


# Functional Requirements:

- Search Functionality:

Allow customers to search for hotels based on various criteria (e.g., location, price, amenities).

Example: A customer searches for hotels in Accra with a pool.

- Booking Functionality:

Enable customers to book rooms.

Example: A customer books a room for a weekend trip.

- Payment Processing:

Integrate with third-party payment services for processing payments.

Example: Using a payment gateway to handle credit card transactions.

- Data Sync and Caching:

Use Redis for caching frequently accessed data and syncing with messaging queues.

Example: Caching search results for popular destinations to reduce load times.

Non-functional Requirements:

- Usability:

The system should be user-friendly and easy to navigate.

Example: A clean and intuitive interface for searching and booking hotels.

- Availability:

Ensure the service is available 24/7.

Example: Using redundant servers to ensure continuous availability.

- Performance:

Fast response times for search queries and booking processes.

Example: Search results are returned within 2 seconds.

- Scalability:

Ability to handle increasing user loads.

Example: Scaling the search service to handle a surge in traffic during holiday seasons.




# View Booking Service

# Functional Requirements:

- Booking History:

Allow users to view their past and current bookings.

Example: A customer checks their booking history for a previous stay.

- Notification System:

Send notifications to users about booking updates and offers.

Example: A customer receives a notification about a new promotional offer.

# Non-functional Requirements:

- Performance:

Fast loading times for booking history.

Example: Booking history data is fetched within 3 seconds.

- Scalability:

Ability to handle a growing number of users and bookings.

Example: Supporting millions of users and their booking data without performance degradation.

- Reliability:

Ensuring data consistency and reliability.

Example: Using backup systems to prevent data loss.

- Security:

Protect user data and booking details.

Example: Using encryption for storing sensitive booking information.



# Final Design

# Functional Requirements:

- Data Processing and Storage:

Process and store data for big data analysis.

Example: Using Hadoop for storing large volumes of booking data for analysis.

- Notification System:

Handle notifications for both customers and managers.

Example: Sending a notification when a booking is confirmed.

# Non-functional Requirements:

- Scalability:

Handle large-scale data processing and storage.

Example: Scaling the Hadoop cluster to accommodate growing data.

- Performance:

Efficient data processing for real-time analysis.

Example: Processing data in real-time using Apache Streaming services.

- Reliability:

Ensure continuous and accurate data processing.

Example: Using fault-tolerant systems to ensure no data loss during processing.

- Security:

Securely handle and store data for analysis.

Example: Implementing access controls and encryption for sensitive data.




# Use Case Diagrams

Actors: Represent users or systems interacting with the system. They can be human users, 
other systems, or devices. Actors are essential for understanding who interacts with the system and what roles they play.


Example: A customer booking a hotel room, a manager updating hotel information.
Use Cases: Represent specific functionalities or actions that the system can perform to
achieve a goal. Use cases are typically depicted by ovals in the diagram and help in understanding 
the system's behavior from a user's perspective.


Example: "Search Hotel," "Book Hotel," "Update Room Rates."
System Boundary: Defines the scope of the system, indicating what is included in the system and what is external to it. 
It helps in clearly delineating the system's boundaries and setting expectations about its interactions with external entities.


- Relationships: Show how actors and use cases interact within the system. 
Relationships include associations between actors and use cases, as well as more complex interactions like extensions and inclusions.
These relationships provide a deeper understanding of how different components of the system interact.



# Benefits:

- Clarity and Communication: Use case diagrams provide a visual representation of the system's functionality and user interactions, 
making it easier to communicate complex ideas and requirements among stakeholders, developers, and users.


- Requirement Identification: By outlining the system's functionalities and interactions,
use case diagrams help in identifying and documenting the functional requirements of the system,
ensuring that all necessary functionalities are considered and captured.


- System Scope Definition: The diagrams clearly define the boundaries of the system, 
illustrating what is included in the system and what is not. This helps in managing project scope, 
setting clear expectations, and avoiding scope creep.


- User-Centric Design: Focusing on user interactions in use case diagrams ensures that the system is designed with the end user in mind.
By aligning system functionalities with user needs and goals, the resulting system is more user-friendly and intuitive.


- Early Validation: Stakeholders can validate requirements and use cases early in the development process through use case diagrams.
This early validation reduces the risk of misunderstandings, ensures that the system meets user needs, 
and helps in delivering a more successful product.


- Planning and Estimation: Use case diagrams aid in project planning and estimation by providing a visual overview of the system's functionalities.
This clarity helps in resource allocation, timeline estimation, and overall project management, 
leading to more accurate planning and successful project execution.






# Acceptance Criteria

Acceptance Criteria are the conditions that a product or system must meet to gain approval from users, customers, or stakeholders. 
They establish predefined requirements to validate the system's performance. Here are several reasons why acceptance criteria are
important and essential in requirement analysis


- Clarity and Communication: Acceptance criteria offer a clear, precise description of required actions, 
ensuring a shared understanding among all stakeholders. This minimizes the risk of misunderstandings and 
misinterpretations among developers, testers, and business analysts.



- Scope Definition: They define the feature or user story's scope by outlining inclusions and exclusions. 
This aids in managing expectations and preventing scope creep, where additional features are added without corresponding
increases in resources.



- Testability: Providing a basis for test case creation, acceptance criteria specify the conditions for feature completion 
and functionality validation. This facilitates testers in validating functionality and helps developers meet requirements.



- Quality Assurance: By setting success conditions, acceptance criteria ensure that the final product meets quality standards. 
Early defect identification enhances system reliability and quality.


- User-Centric Approach: Often framed from the user's viewpoint, acceptance criteria align the development process with user needs, 
enhancing the user experience of the product.

- Project Management: They act as a tracking tool for project managers to monitor progress and determine feature or user story completion. 
This aids in adhering to timelines and keeping the project on schedule.



# Example of Acceptance Criteria for the Checkout Feature in the Booking Management System

Feature: Checkout Acceptance Criteria:

# Valid Booking Details:

Given a customer is on the checkout page,
When the customer reviews their booking details,
Then the booking details (hotel name, room type, check-in and check-out dates, total cost) must be accurately displayed.


# Payment Method Selection:

Given a customer is on the checkout page,
When the customer chooses a payment method,
Then the system should display all available payment options (credit card, debit card, PayPal, etc.).


# Payment Processing:

Given a customer has selected a payment method,
When the customer enters valid payment information and submits the payment,
Then the system should process the payment and display a confirmation message if the payment is successful.


# Error Handling for Invalid Payment:

Given a customer has selected a payment method,
When the customer enters invalid payment information and submits the payment,
Then the system should display an appropriate error message and prompt the customer to correct the information.


# Booking Confirmation:

Given a customer's payment is successfully processed,
When the system confirms the payment,
Then the system should generate and display a booking confirmation page with the booking details 
and send a confirmation email to the customer.


# Cancellation Option:

Given a customer has completed a booking,
When the customer navigates to their booking history,
Then the customer should have the option to cancel their booking, provided the cancellation policy allows it.



