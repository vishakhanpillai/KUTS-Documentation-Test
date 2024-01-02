<h3 align='center'> <u>Kerala Unified Transport System (KUTS) </u> </h3>
<h4 align='center'>A Seamless Transition from Paper to Digital System for Passenger Convenience<h4>
<hr>

## Table of Contents

1. [Introduction](#kuts_intro)
2. [Objectives](#kuts_objectives)
3. [Methodology](#kuts_methodology)
4. [Disadvantages of the Current System](#kuts_disadv)
5. [Advantages of Proposed System](#kuts_adv)
6. [Risk Analysis](#kuts_risks)
7. [Feasibility Study](#kuts_fstudy)
8. [System Requirements](#kuts_sysreq)
9. [Module Description](#kuts_moddesc)
    - [Admin](#kuts_admin)
    - [User](#kuts_user)
    - [Bus Owner](#kuts_busowner)
    - [Conductor](#kuts_conductor)
10. [Design Modelling (Data Flow Diagram)](#kuts_design)
    - [Level 0](#kuts_level0)
    - [Level 1.0 - Admin](#kuts_level1.0_admin)
    - [Level 1.1 - Passenger](#kuts_level1.1_passenger)
    - [Level 1.2 - Operator](#kuts_level1.2_operator)
    - [Level 1.3 - Conductor](#kuts_level1.3_conductor)

## Introduction <a name="kuts_intro"></a>

The project aims to address the current shortcomings of the paper-based ticketing system in bus transportation by proposing the implementation of a mobile application alongside the existing system, gradually phasing out the outdated paper tickets. The goal is to improve efficiency, provide proper timetables, introduce alternative payment options, and ensure convenient access for students while preserving the use of paper-based records.

## Objectives <a name = "kuts_objectives"></a>

- Develop a mobile application that coexists with the current paper-based system to enhance the overall efficiency of bus ticketing.
- Provide accurate and easily accessible timetables within the app to assist passengers in planning their journeys effectively.
- Introduce alternative payment options such as contactless cards or mobile payments to reduce reliance on coins and facilitate a smoother transaction process.
- Implement a secure and reliable method to store and retrieve students' details through a QR code or similar mechanism to make sure students receive the compensation they are entitled to. Improve student convenience by ensuring smooth acceptance of digital passes by bus conductors, eliminating arbitrary disallowance based on misguided reasons.
- Enhanced analytics systems collect and analyze data on passenger patterns, including peak hours, popular routes, and passenger demographics, to help bus operators make informed decisions regarding route planning, fleet management, and resource allocation. Generate reports and visualizations that highlight key performance indicators such as passenger count, ticket sales, and revenue, enabling bus operators to assess the effectiveness of their services and identify areas for improvement

## Methodology <a name="kuts_methodology"></a>

- Conduct a comprehensive analysis of the existing paper-based ticketing system, including its shortcomings and limitations.
- Design and develop a user-friendly mobile application that integrates essential features such as timetables, payment options, and student pass management.
- Implement a robust and secure backend system to handle student details, utilizing QR codes or unique identifiers for easy retrieval and verification.
- Collaborate with bus operators, educational institutions, and relevant stakeholders to ensure seamless integration and acceptance of the digital ticketing system.
- Perform pilot testing and gather feedback from users to fine-tune the application and address any usability concerns.
- Execute a phased implementation plan, gradually reducing the reliance on paper-based tickets while ensuring a smooth transition for both passengers and bus operators.
- Continuously monitor and evaluate the performance of the digital ticketing system, making necessary improvements based on user feedback and emerging technologies.
- Implement a robust data collection mechanism within the digital ticketing system to capture relevant information, such as ticket sales, passenger counts, payment methods, and journey details. This data can be stored securely in a centralized database.

## Disadvantages of the Current System <a name  = "kuts_disadv"></a>

- **Inefficiency** : Paper-based ticketing systems can be time-consuming and inefficient, especially during peak hours or when there is a large number of passengers boarding the bus. The process of issuing and collecting paper tickets takes time and can lead to delays in boarding, causing inconvenience to passengers.
- **Confusing and Inconvenience** : Passengers who are not native to a city often face the disadvantage of being left confused and inconvenienced due to the lack of proper timetables and a centralized way to access information about different bus routes and timings. This absence of readily available and easily accessible information makes it challenging for non-native passengers to plan their journeys effectively, leading to confusion, potential delays, and a sense of disorientation. Without a centralized system providing comprehensive route and timetable information, these passengers are left to rely on fragmented or unreliable sources, further exacerbating the difficulty of navigating the public transportation system in an unfamiliar city
- **Inequitable Denial to Students** : The denial of concessions to eligible students by private bus operators in Kerala, despite the existing policy, creates an inequitable situation, hampers affordability, and denies them the basic right provided to them by the government.
- **Limited payment options** : The current system only accepts cash payments, limiting the flexibility of payment options for passengers. A new system should aim to provide multiple payment options, such as credit/debit cards, mobile wallets, and net banking, to improve convenience and accessibility for
  passengers.
- **Lack of analytics** : Paper tickets do not provide real-time data on passenger patterns, journey times, or ticket utilization. This makes it challenging for bus operators to analyze and optimize their services based on accurate data. It also limits their ability to make informed decisions regarding route planning,capacity management, and service improvements.
- **Inability to book tickets online** : Current systems do not provide an online booking feature. This makes it inconvenient for passengers who have to physically visit the ticket counter to purchase tickets. The lack of an online booking system also limits the ability of bus operators to manage passenger demand and capacity in an optimal way
- **Lack of contactless payment options** : Implementing contactless payment methods, such as mobile payments or contactless cards, will not only address health concerns but also improve overall convenience and efficiency for passengers, allowing for faster transactions and reducing the reliance on cash handling, thereby streamlining the ticketing process.
- **Poor user experience** : Existing ticketing systems can be difficult to use, especially for passengers who are not familiar with the system(such as tourists). The new system should aim to provide a user-friendly interface that is easy to navigate, with clear instructions and intuitive design.
- **Environmental impact** : Paper tickets contribute to deforestation and have a negative impact on the environment. The production, distribution, and disposal of paper tickets require significant amounts of paper and energy, contributing to carbon emissions and waste generation.

## Advantages of Proposed System <a name = "kuts_adv" ></a>

- **Convenience and Efficiency** : The digital ticketing system provides a convenient and efficient way for passengers to purchase and manage their tickets. With options like mobile apps or contactless cards, passengers can easily access and use their tickets without the need for physical paper tickets or exact change.
- **Contactless Payment** : The system enables contactless payment options, which have become increasingly important, especially in light of the COVID-19 pandemic. Passengers can make payments through mobile wallets or contactless cards, reducing the risk of transmission and providing a safer and hygienic payment method.
- **Timetable and Route Accessibility** : The mobile application can include comprehensive and up-to-date timetables and route information, allowing passengers to access accurate and real-time schedules. This improves passengers' ability to plan their journeys and reduces confusion or delays caused by the lack of proper timetables in the current system.
- **Enhanced Student Pass Management** : By incorporating a QR code or similar mechanism, the proposed system simplifies student pass management. Students' details can be stored securely and retrieved easily, eliminating the need for physical passes. This reduces the likelihood of disallowance based on invalid or misplaced passes, providing a fair and efficient process for student transportation.
- **Data Insights and Analytics** : The digital ticketing system enables the collection and analysis of passenger data, providing valuable insights to bus operators. Analyzing passenger patterns, peak hours, and ticket sales trends allows for better resource allocation, route optimization, and service planning. These data-driven insights help enhance operational efficiency and improve the overall transportation experience.
- **Reduced Environmental Impact** : By transitioning from paper tickets to digital ticketing, the proposed system contributes to a reduction in paper usage. This has a positive environmental impact by conserving resources, reducing waste, and lowering carbon emissions associated with ticket printing and disposal.
- **Passenger Feedback** : The bus review system provides passengers with a platform to express their opinions and provide feedback on various aspects of their journey, such as cleanliness, punctuality, driver behavioral, and overall service quality. This feedback can help bus operators identify areas for improvement and address specific concerns raised by passengers.

## Risk Analysis <a name = "kuts_risks"></a>

- **Technical Challenges** : The adoption of new technology can introduce technical complexities and challenges. Issues such as system compatibility, network connectivity, software bugs, or hardware failures may arise, causing disruptions in the ticketing process and affecting the user experience.
- **Data Security and Privacy** : Storing and managing passenger data in a digital system brings concerns regarding data security and privacy. Adequate measures must be in place to protect sensitive information, such as personal details and payment data, from unauthorized access, data breaches, or cyber-attacks.
- **Resistance to Change** : Introducing a new system may face resistance from both passengers and bus operators accustomed to the traditional paper-based ticketing system. Overcoming resistance to change, addressing concerns, and providing sufficient training and support are crucial for successful implementation.
- **Integration with Existing Systems**: Seamless integration of the digital ticketing system with existing systems, such as fare collection and accounting systems, is crucial. Compatibility issues and potential disruptions during the integration process need to be carefully managed to ensure smooth operations.

## Feasibility Study <a name = "kuts_fstudy"></a>

- **Economic Feasibility** : The software used for developing, testing and maintaining the system is free to use or minimal in cost.
- **Technical Feasibility** : The hardware and the components required for the system are common and can be found in any recently purchased system.
- **Operational Feasibility** : The operational logic required for developing, maintaining and using the system is low-level and easily understandable. 

## System Requirements <a name = "kuts_sysreq"></a>

- **Operating System** : Android 7 or Above
- **RAM** : 4GB or Above
- **Processor** : Dual Core Processor or Better
- **Constant GPS & Stable Internet Connection**
- **Rear Camera** : 2MP or Better

## Module Description <a name = "kuts_moddesc"></a>

**1. Admin** <a name = "kuts_admin"></a>
  - Register
  - Login
  - Manage Timetables
  - Manage Passengers
  - Manage Students Pass verification
  - Manage Offers
  - View Feedback
  - Delete Feedback

**2. Passenger** <a name = "kuts_passenger"></a>
  - Register
  - Login
  - View Ticket Available
  - Buying Ticket
  - Route Map Display
  - View Timetable
  - Post Review
  - Delete Review
  - View Reply
  - View Past Tickets
  - View Nearby Stops
  - Delete Review
  - Delete User Account

**3. Operator** <a name = "kuts_operator"></a>
  - Registration
  - Login
  - Manage Bus Info
  - Register Conductors
  - Manage Conductors
  - View Analytics
  - View Review
  - Reply To Review
  - Delete Owner Account


**4. Conductor** <a name = "kuts_conductor"></a>
  - Login
  - Verify Tickets
  - Update Bus Status
  - Manage Timetable
  - Update Bus Position

## Design Modelling (Data Flow Diagram) <a name = "kuts_design"></a>

### Level 0 <a name = "kuts_level0"></a>
  ![kuts_level0_img](images/Level%200%20KUTS.jpg)

### Level 1.0 - Admin <a name = "kuts_level1.0_admin"></a>
  ![kuts_level1.0_img](images/Level%201.0%20KUTS.jpg)

### Level 1.1 - Passenger <a name = "kuts_level1.1_passenger"></a>
  ![kuts_level1.1_img](images/Level%201.1%20KUTS.jpg)

### Level 1.2 - Operator <a name = "kuts_level1.2_operator"></a>
  ![kuts_level1.2_img](images/Level%201.2%20KUTS.jpg)

### Level 1.3 - Conductor <a name = "kuts_level1.3_conductor"></a>
  ![kuts_level1.2_img](images/Level%201.3%20KUTS.jpg)


