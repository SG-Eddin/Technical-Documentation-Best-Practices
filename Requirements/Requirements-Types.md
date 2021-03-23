# Requirements Types
To get the most out of the requirements, you need to think of it as:
- A list of features which should be included in the final version of the product.
- A let of description of how the product should perform in different situations.
- The reason why that product should exit in the first place.

This will help you to describe:
- What the product should be like.
- How it should work.
- Why it should be done in the first place.

Now, let's see the requirements' types that will bring these points together:

1. [Business Requirements](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/Requirements/Requirements-Types.md#business-requirements)
2. [Business Rules](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/Requirements/Requirements-Types.md#business-rules-restrictions)
3. [User Requirements](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/Requirements/Requirements-Types.md#user-requirements) 
4. [Solution Requirements](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/Requirements/Requirements-Types.md#solution-requirements)
   - Functional Requirements. What the product should do or support?
   - Non-Functional Requirements. How well a product must perform (the quality factor of the product).
5. [Development Constraints Requirements](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/Requirements/Requirements-Types.md#development-constraints-requirements)

## Business Requirements
Business requirements answer the question of *'Why the product should be created?'*. It outlines the purpose of a software project and the reason why the client wants this project.

> The business requirement must define the tangible and quantifiable business value.
> It is the way for business analysts to review the goals of the product.

## Business Rules (restrictions)
Business rules falls under the buisness requirements and are **more specific** than buisness requirements. 
It answers the question of *'What rules must be followed while building the product?'*
> Business rules constrain how the product must function appropriately to serve the business need.

Examples:
- Privacy policy
- Branding uniformity (the product must be developed to be visually consistent with other products of the client.
- Government regulation (such as maintaining user data, things related to laws).

## User Requirements
Outline what tasks end-users can do with the product and how they will engage with the product.
It can be identified as the core requirements of the product being developed.

> User requirement may be the most important requirement for the development team to get right.

User Requirement can be presented in some forms such as:
- Use Cases
- User Stories
- Story Boards

## Solution Requirements
Solution requirements falls under the scope of the development team, they are:
- Functional
- Non-Functional


Functional Requirements | Non-Functional Requirement
------------------------|---------------------------
The product features or functions that the developers must implement to enable users to do stuff, they describe the system beahviour under specific conditions. | Serves as a description of how well a product must perform. It is the quality factor of the product and sometimes referred to as the quality requirements.
Expressed with **inputs** and **outputs** and a **description of the behaviour** itself. | Are represented in: Accuracy and safety, Dependability, Security, Usability, Efficiency, Performance, Maintainability.
You have to be specific in taking requirement to avoid problems in planning.|
One way to represent functional requirements is by using flow diagram which displays the data flow and dependencies of the system components as a whole and how individual components are stitched together. ![Example of Flow diagram](https://user-images.githubusercontent.com/60129693/112131246-0ba9c300-8bd2-11eb-85a2-f2ac5dde77b9.png)|

## Development Constraints Requirements
Outline the implementation technology, conventions, documentation, and the process which the team will use. Descussion which devices or platforms the development team will support.








