# Requirements Writing Types
To get the most out of the requirements, you need to think of it as:
- A list of features which should be included in the final version of the product.
- A let of description of how the product should perform in different situations.
- The reason why that product should exit in the first place.

This will help you to describe:
- What the product should be like.
- How it should work.
- Why it should be done in the first place.

Now, let's see the requirements' types that will bring these points together:

1. [Business Requirements](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Types.md#business-requirements)
   - [Business Rules](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Types.md#business-rules-restrictions)
2. [User Requirements](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Types.md#user-stakeholder-requirements) 
3. [Solution Requirements](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Types.md#solution-requirements)
   - [Functional](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Types.md#functional-requirements) (What the product should do or support?)
   - [Non-Functional](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Types.md#non-functional-requirements) (How well a product must perform (the quality factor of the product)?)
4. [Development Constraints Requirements](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Types.md#development-constraints-requirements)
5. [Interface Requirements](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Types.md#interface-requirements)

-----------------------------------------------------------------------------------------------------------------------

## Business Requirements
Business requirements answer the question of *'Why the product should be created?'*. It outlines the purpose of a software project and the reason why the client wants this project for their business *not how*.

- Business requirements are a high-level features of the system.
- It is usually written in [Traditional (Text-Based) style](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Styles.md#2-traditional-text-based).

*Example:
Provide an SMS notification system for college students.*

> This type does not include an actor, just a capability.
> The business requirement must define the tangible and quantifiable business value.
> It is the way for business analysts to review the goals of the product.


### Business Rules (restrictions)
Business rules falls under the buisness requirements and are **more specific** than buisness requirements. 
It answers the question of *'What rules must be followed while building the product?'*
> Business rules constrain how the product must function appropriately to serve the business need.

Examples:
- Privacy policy
- Branding uniformity (the product must be developed to be visually consistent with other products of the client.
- Government regulation (such as maintaining user data, things related to laws).

----------------------------------------------------------------------------------------------------------------------

## User (Stakeholder) Requirements
User Requirements outline what tasks end-users can do with the product and how they will engage with the product.
It can be identified as the core requirements of the product being developed.

- Written from the prespective of the user.

- It is usually written in [Traditional (Text-Based) style](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Styles.md#2-traditional-text-based).

*Example:
A student shall be able to receive an SMS notification when their certificate is ready to pick up.*

- User requirements can also be written in the form of a [User Story](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Styles.md#1-user-stories).

*Example:
As a student, I want to receive an SMS message when my certificate is ready so that I know when to go to the college to collect it.*

> User requirement may be the most important requirement for the development team to get right.
----------------------------------------------------------------------------------------------------------------

## Solution Requirements
Solution requirements falls under the scope of the development team, they are:
- [Functional](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Types.md#functional-requirements)
- [Non-Functional](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Types.md#non-functional-requirements)

### Functional Requirements

- The product features or functions that the developers must implement to enable users to do stuff, they describe the system beahviour under specific conditions.
- Expressed with **inputs** and **outputs** and a **description of the behaviour** itself.
- You can represent functional requirements - visually - by using flow diagram which displays the data flow and dependencies of the system components as a whole and how individual components are stitched together.
 
![Picture1](https://user-images.githubusercontent.com/60129693/112746773-6156e480-8fb1-11eb-97be-3cf1521e194b.png)

- Can be written as [User Stories](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Styles.md#1-user-stories).
*Example: "As a college administrator, I want to update the student's phone number so that they can receive SMS messages"*

- You have to be specific in taking requirement to avoid problems in planning.

- Can also be written as a [Use Case](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/System-Documentation.md/Requirements.md/Requirements-Writing-Styles.md#3-use-cases).

*Example:*

![Functional requirements](https://user-images.githubusercontent.com/60129693/112756320-eb6c7080-8fe4-11eb-9c24-51b27c816a50.jpg)


### Non-Functional Requirements
- Serves as a description of how well a product must perform. It is the quality factor of the product and sometimes referred to as the quality, constraints, non-behavioral requirements.
- Are represented in: Accuracy and safety, Dependability, Security, Usability, Efficiency, Performance, Maintainability.
- Can be written in the three writing styles as the following examples:

User Stories | Traditional (Text-Based) | Use Case
-------------|---------|-------------
As a college administrator, I want the system to display pages within 3 seconds of navigating so that I can do the task quickly and efficiently. | The system shall display all system pages within 3 seconds of user navigation to them. | Fill in the Use case form including the Use Case number, Title, Description,... etc. and then add a field of Non-Functional requirements *The system shall display all system pages within 3 seconds of user navigation.*


---------------------------------------------------------------------------------------------------------------------------------------------------------------
## Development Constraints Requirements
Outline the implementation technology, conventions, documentation, and the process which the team will use. Descussion which devices or platforms the development team will support.

------------------------------------------------------------------------------------------------------------

## Interface Requirements
Describes how a system will interact with another system; hardware, software, communication, and user interfaces.

- It can be written as:

  - Traditional (Text-Based) as in the following example: 
    
    *The system shall send SMS messages by utilizing the SMS APIs*

  - Use Case as in the following example: 
    
    *Fill in the Use Case form and add a section for Interface: "The system shall send SMS messages using the SMS APIs."*

- You can add wireframes or mockups, or a style guide to outline your requirements. 
   
   Example: *Red font for error messages, what shape of buttons... etc.*







