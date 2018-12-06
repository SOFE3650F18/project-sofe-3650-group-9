### Step 1 & 2: Establishing Iteration Goals by Selecting Drivers.
Building on the fundamental structural decisions made in the previous two iterations, we can start to look into the completion of some of the more relevant quality attributes. This particular iteration will focus on QA-4.

### Step 3: Choose One or More Elements of the System to Refine.
Elements that are needed to be refined:
- Course and Enrolment Information.
- Update Course Information.

### Step 4: Choose One or More Design Concepts That Satisfy the Selected Drivers.
| Design Decisions and Location | Rationale |
| --- | --- |
| Maintain visibility of the system status on web pages accessed by the user | Ensuring that the user is aware of the state system through appropriate feedback decreases confusion and increases usability of the system|
| Implement emergency exits in cases where user input is necessary for a specific function of the system | Giving the user an “undo” function allows for the user to recall the system from an unwanted state without having to go through an extended dialogue, increasing usability. 
| Implement a course enrollment option from the course information page. | This gaurentees that related information is grouped together, making it straightforward for the user to enroll in classes |
| Update the database after every enrollment option processed by the web application | Because of the user's need for the most recent information, information relating to the course needs to be updated after every course action (i.e enroll, drop course, update course capacity, etc.) in order for the user to have a clear idea of all aspects of the course |

### Step 5: Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces.
| Design Decisions and Location | Rationale |
| --- | --- |
| Course and enrolment information should be easily found by the user.  | The user should be able to find info relevant to what they need without having to blindly navigate. Information about a course and its enrolment should be a maximum of 2 pages away. |
| Any changes to the course and enrolment information should be updated right away. | The user should be getting the most recent info from the CMS. Dated information would not be beneficial to the user as it may cause issues. |
| Notifications about the courses the user has enrolled in. | If a user has enrolled in a course, they should only get information about that course. The user has no need for information about courses they are not enrolled in. |

### Step 6: Sketch Views and Record Design Decisions.
[](images/image.jpg)

| Design Decisions and Location | Rationale |
| --- | --- |
| Maintain visibility of the system status on web pages accessed by the user | Ensuring that the user is aware of the state system through appropriate feedback decreases confusion and increases usability of the system|
| Implement emergency exits in cases where user input is necessary for a specific function of the system | Giving the user an “undo” function allows for the user to recall the system from an unwanted state without having to go through an extended dialogue, increasing usability. |

### Step 7: Perform Analysis of Current Design and Review Iteration Goal and Achievement of Design Purpose.
| Not Addressed | Partially Addressed | Completely Addressed | Design Decisions Made During the Iteration |
| --- | --- | --- | ---- |
|  | UC-1, UC-3 |  | Associative use cases have been touched on but not primary focus in this iteration. |
|  |  | UC-2 | Models and diagrams to support this use case have been created in previous and this iteration. |
|  |  | UC-4 | Models and diagrams to support this use case have been created in previous and this iteration. |
|  |  | UC-5 | Models and diagrams to support this use case have been created in previous and this iteration. |
|  |  | UC-6 | Models and diagrams to support this use case have been created in this iteration. Updating any changed info about a course to the user as well as making it easier to navigate the CMS allow for this use case to be resolved. |
|  |  | UC-7 | Models and diagrams to support this use case have been created in this iteration. This use case has been investigated by implementing a notification system that sends the user relevant information about enrolled courses. |
|  |  | UC-8 | Models and diagrams to support this use case have been created in this iteration. Designing a system that constantly updates course and enrolment info in the CMS. |
|  |  | UC-9 | Models and diagrams to support this use case have been created in this iteration. Info on course enrolment will be easy to find in the CMS as well as any changes to enrolment will be updated. |
| QA-1, QA-6 |  |  | Not addressed in this iteration. |
|  | QA-2 |  | Relates to associated use case (UC-5) which has been described in previous iteration. |
|  | QA-3 |  | Relates to associated use case (UC-4) which has been described in previous iteration. |
|  | QA-4 |  | Relates to all of the use cases, more specifically UC-2, UC-6, UC-7, UC-8, UC-9. This iteration makes design decisions that benefit the user by making relevant info easier to find as well as providing updated info. |
|  | QA-5 |  | Relates to associated use case (UC-1, UC-5) which has been described in previous iteration. |
| CON-2, CON-4 |  |  | Not addressed in this iteration. |
|  | CON-1 |  | Identified and modules relating to the issue have been investigated. |
|  | CON-3 |  | Identified and modules relating to the issue have been investigated. |
|  | CON-5 |  | Identified and modules relating to the issue have been investigated. |
|  | CON-6 |  | Identified and modules relating to the issue have been investigated. |
