# Requirements Writing Styles
There is no right or wrong in choosing the style of writing the requirements. It is based on the level of details and the specifications required by your project.

![](https://user-images.githubusercontent.com/60129693/112272752-402a8700-8c85-11eb-8f07-944adc60aa27.png)



- [User Stories](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/Requirements/Requirements-Writing-Styles.md#user-stories)
- [Traditional (Text-Based)](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/Requirements/Requirements-Writing-Styles.md#traditional-text-based-requirements-structure-and-design)
- [Use Cases](https://github.com/SG-Eddin/Technical-Documentation-Best-Practices/blob/main/Requirements/Requirements-Writing-Styles.md#use-cases)


## User Stories
In agile (and its frameworks: scrum and kanban): A user story is an informal, general explanation of a software feature written from the perspective of the end user or customer. The purpose of a user story is to articulate how a piece of work will deliver a particular value back to the customer.
User story is one or more sentence(s) in a simple language or a business language that captures what users need to do.

User stories are meant to keep all of the requirements of your system to a consistent format. They are easy to write, to read, and easy to evaluate.

On a project, you and your team decide if this is the best way to follow.

### User Stories Structure and Design

Item | Description
------------|-------
**Format:** | As a ```<type of user>```, I want to ```<task/function>```, so that ```<reason>```
**Examples 1:**| 1: *As a <**patient**>, I want <**to receive an SMS when my prescription is ready to pick up**>, so that <**I can avoid unnecessary waiting at the pharmacy**>*
**Example 2:**| 2: *As a <**pharmacist**>, I want to <**enroll a patient in the SMS notification service**>, so that <**they can receive notifications when their prescriptions are ready to pick up**>*
**Benefits:**| Brief, understandable by users and developers, iterative, and easy to estimate effort.
**Limitations:**| Lack of performance and non-functional details, and open to interpretation.

### Practice
User stories are typically written on cards or sticky notes and pasted on a wall or a board where the whole team can see them. 

During the development phase, these sticky notes with the user stories are pasted on the backlog column, team members take off the sticky note (with the user story) and place it on a column of Work in Progress (WIP).

This visualizes what's done, what's in progress, and what's not started.

### Acceptance Criteria
User stories are used with Acceptance Criteria which certifies that User Stories are complete or working as intended.
The Acceptance Criteria helps addressing some of User Stories' limitations such as the incomplete information or being limited and not clear how to be implemented correctly.

*Example*:
User Story | Acceptance Criteria
---------- | --------------------
As a <**pharmacist**>, I want to <**enroll a patient in the SMS notification service**>, so that <**they can receive notifications when their prescriptions are ready to pick up**> | - A pharmacist must complete all the required fields before submitting the enrollment form.
.. |- Information from the form is stored in the enrollment database.
.. |- A confirmation SMS is sent to the patient upon successful enrollment.
.. |- A pharmacist can view the enrollment status of a patient.

--------------------------------------------------------------------------------------

## Traditional (Text-Based)
Traditional (text-based) requirements document business or functional specifications. They describe in detail what the business is expecting the technical team to provide.

### Traditional (Text-Based) Requirements Structure and Design

Item | Description
-----|-------
**Format:** | ```<Subject (system/user) doing the action>```, ```<Auxiliary (supplementary) verb>```, ```<capability or functionality to be provided>```, *(optional component)* ```<criterion that limits or further explains requirement>```
**Example 1:** | *<**The Company**> <**shall**> <**develop an SMS notification system**> enabling patients to <**Receive alerts when their prescriptions are available to pick up**>*
**Example 2:** | *<**The Pharmacy System**> <**shall**> provide the ability to <**enroll patients in a notification service**>*.
**Benefits:** | Can be used to caputre requirements early in the project with details more than the user stories.
**Limitations:** | May lack details for implementation.

> Auxiliary Verbs According to IEEE
> Word | Indicates | Example
> -----|---------- | --------
> Shall| Mandatory requirement = *is required to* | The user *shall* be able to log into the system.
> Should | Preferred possibility among several options = *is recommended that* | The system *should* send a notification within 10 sec. (it could be 10 or 20 sec.)
> May | A permissible course of action = *is permitted to* | The pharmacist *may* create multiple prescriptions.
> Can | Used for statements of possibility and capability = *is able to* | The user *can* customize the profile page color.
> Must | Only used to describe unavoidable situations (not mandatory requirements) = *is natural consequence of* | The system *must* stop sending SMS messages after 3 failed attempts.
> Will | Only used in statements of fact (not mandatory requirements) = *it is true that* | The pharmacy web app. *will* require internet access.

----------------------------------------------------------------------------------------------------------------------------------------------------
## Use Cases
Use Case i s alist of actions or steps defining the interaction between a user and a system to achive a goal.
AIt is a written description of how users will perform tasks on the system. It outlines, from a user's point of view, a system's behavior as it responds to a request.
Each use case is represented as a sequence of simple steps, beginning with a user's goal and ending when that goal is fulfilled.

### Use Cases Structure and Design

Format |  .. 
-----|-------
**Use Case Number:** | A unique identifier for this use case.
**Title:** | An active-verb goal phrase that names the goal of the primary actor.
**Description:** | Brief description and purpose of the use case.
**Actors:** | All actors involved in the use case, both primary and secondary.
**Scope:** |  Name of system or subsystem defined by the use case.
**Priority:** | How important is this requirement?
**Assumptions:** | Any conditions presumed to be true.
**Preconditions:** | State the system must be in for the use case to proceed.
**Postconditions** | Changes in the environment as a result of the use case.
**Trigger:** | What caused this use case to run.
**Main Success Case Scenario:** | Step-by-step use case scenarion.
**Alternative Flow** | Means of achieving the stated goal, including error conditions.




