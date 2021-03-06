# Writing Good Requirements

To build a successful requirement document, you need to understand what your users need, as it leads the project to be successful, challenged, or to fail.

* **Successful**
 1. On time
 2. On budget
 3. Satisfactory results.

* **Challenged:**
The project is delivered but:
 1. Over time
 2. Over budget
 3. Features and functionality must be modified.

![Project Challenged Factors](https://user-images.githubusercontent.com/60129693/111955949-db3f2780-8af2-11eb-8906-57e526ebb3de.jpg)

* **Failed:** 
The project is cancelled during the development cycle.

![Why Software Projects Fail](https://user-images.githubusercontent.com/60129693/111956021-f447d880-8af2-11eb-83ef-b43410acd0ea.jpg)

# Best Practice
The best practice is to write a requirement document using a single and consistent template that all team members adhere to.



## Characteristics of Writing Good Requirements
There are some characteristics of good requirements, they should be:

1. **Cohesive:** Each requirement addresses only one thing.
2. **Concise:** Don't ramble and write into the point.
3. **Complete:** All the information is in one place with no missing information or extension in emails...etc.
4. **Consistent:** Does not contradict with any other requirement, and is consistent with all other documents.
5. **Atomic:** Does not contain conjunctions.
``` text
Example:
Wrong: User selects (item) and (item)
Correct:
1. User selects (item),
2. User selects (item)
```
5. **Traceable:** All requirements should be documented so that no requirement pop up in the middle of the development and no one knows where it came from.
6. **Current:** Not obsolete.
7. **Unambiguous:** consise and without jargon, accrynoms, and only interpreted in one way and not uderstood differently by many people.
8. **Specify Importance:** Specifies a level of importance defined by stakeholders/time/budget ```must do/should do/could do```.
9. **Verifiable:** After it is done, it can be tested and verified.

## Perspective
While writing, there are two perspectives to consider: 
- User Perspective
- System Perspective

User Perspective            |  System Perspective            
----------------------------|--------------------------------
Writing what users expect from the product. | Happens in the back-end and the user doesn\t see it.
**User type:** ```Actor name (i.e. Administrator)``` | **Conditions:** ```when [some conditions are met]```
**Result:** ...shall be able to ```[do something]```| **Result:** the system shall ```[do something]```
**Object:** ... ```[to something]```|
**Qualifier:** *optional* ```[response time goal or quality object]```| **Qualifier:** *optional* ```[response time goal or quality object]```
*Example:* The administrator shall be able to sign in into the system through admin creditials only | *Example:* When an online purchase is done, the system shall send an SMS within 30 seconds.

## Tips for Writing Clear Requirements

Do | Don't            
---|-------
Use terms consistently. If you used a term like 'notifications' in a place, use it along the whole document and don't change it. | Don't design the system (don't specify UI controls, types of controles, component names, or database fields). In the requirements phase, the focus is only on functionality and what the users need.
Create a glossary to define terms. | Don't use vague terms (user-friendly, efficient, high-performance, approximately, several), instead, use terms that can be quantified.
Use active voice. | Don't use terms like (usually, often, typically) 
Avoid negation (without, cannot, ...etc.) to avoid confusion. Example: *Users ~~without~~ an account ~~cannot~~ log into the system.* Correction: *Only users with valid accounts can log into the system*. | Don't express possibilities (could, ought to, probably).
