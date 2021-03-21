# Writing Requirements
                      Poor Requirements = Project Failure
Requirements are Functional and Non-Functional.
## Functional Requirements
Functional requiremets are the product features or functions that the developers must implement too enable users to do stuff.
They describe the system beahviour under specific conditions.
To build a successful requirement document, you need to understand what your users need, as it leads the project to be successful, challenged, or to fail.

> **Successful**
> 1. On time
> 2. On budget
> 3. Satisfactory results.

> **Challenged**
The project is delivered but:
> 1. Over time
> 2. Over budget
> Features and functionality must be modified.

> **Fail** 
> The project is cancelled during the development cycle.

Requirements are translations from users language to developers language.

## Characteristics of requirements
There are some characteristics of good requirements, they should be:

1. **Cohesive** Each requirement addresses only one thing.
2. **Complete** All the information is in one place with no missing information or extension in emails...etc.
3. **Consistent** Does not contradict with any other requirement, and consistent with all other docs.
4. **Atomic** Does not contain conjunctions.
``` text
Example:
Wrong: User selects (item) and (item)
should be:
1. User selects (item),
2. User selects (item)
```
5. **Traceable** All requirements should be documented so that no requirement pop up in the middle of the development and no one knows where it came from.
6. **Current** Not obsolete.
7. **Unambiguous** consise and without jargon, accrynoms, and only interpreted in one way and not uderstood differently by many people.
8. **Specify Importance** Specifies a level of importance defined by stakeholders/time/budget. ```must have/good to have/nice to have```
9. **Verifiable** After it is done, it can be tested and verified.

## Perspective
While writing, there are two perspectives to consider: 
- User Perspective
- System Perspective

User Perspective            |  system Perspective            
----------------------------|--------------------------------
Writing what users expects from the product.
**User type:** Actor name (ie. Administrator)
**Result:** ...shall be able to [do something].
**Object:** ... [to something]
**Qualifier:** *obtional* [response time goal or quality object]
