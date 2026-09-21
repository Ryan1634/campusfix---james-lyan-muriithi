CampusFix Software Requirements Specification (SRS)

1. Introduction:

1.1 Purpose;
This document describes the requirements for CampusFix, a university facilities maintenance reporting and management system.
The purpose of the system is to provide a centralized way for students and staff to report facilities problems and for maintenance personnel to manage those reports until they are resolved.

1.2 Scope;
CampusFix will allow users to report problems such as broken computers, projectors, lights, doors, water leaks and other facilities-related faults.
The system will record each request and allow authorized personnel to prioritize, assign and update it.

The main process will be:
Report → Triage → Assignment → In Progress → Resolved → Closed

2. Users of the System:
Student/Staff;
A student or staff member can:
- Log into the system
- Report a maintenance problem
- Provide the location of the problem
- Describe the problem
- View their submitted requests
- Check the status of their requests

Maintenance Staff;
Maintenance staff can:
- Log into the system
- View requests assigned to them
- Update the status of a request
- Add information about the work performed
- Add resolution notes

Administrator/Supervisor;
The administrator or supervisor can:
- View maintenance requests
- Prioritize requests
- Assign requests to maintenance workers
- Monitor request progress
- View maintenance statistics
- Manage appropriate system information

3. Functional Requirements
FR-01 — User Login
The system shall allow registered users to log into CampusFix using their credentials.

FR-02 — User Logout
The system shall allow authenticated users to log out of the system.

FR-03 — Submit Maintenance Request
The system shall allow students and staff to submit a maintenance request.

FR-04 — Request Information
A maintenance request shall contain at least:
- Category
- Location
- Description
- Date and time of reporting

FR-05 — Unique Request ID
The system shall generate a unique identification number for every maintenance request.

FR-06 — Request Recording
The system shall save submitted requests in the database.

FR-07 — View Requests
Authorized users shall be able to view maintenance requests according to their role.

FR-08 — Set Priority
An administrator or supervisor shall be able to assign a priority to a maintenance request.
The priority may include:
- Low
- Medium
- High
- Critical

FR-09 — Assign Maintenance Worker
An administrator or supervisor shall be able to assign a maintenance request to a maintenance worker.

FR-10 — Update Status
Maintenance staff shall be able to update the status of an assigned request.
Possible statuses include:
- Submitted
- Assigned
- In Progress
- Resolved
- Closed

FR-11 — Resolution Notes
Maintenance staff shall be able to enter notes describing how a problem was handled.

FR-12 — Request History
The system shall keep a history of important changes made to a request.

FR-13 — Close Request
Authorized users shall be able to close a request after the problem has been resolved.

FR-14 — Search and Filtering
Authorized users shall be able to filter requests based on information such as status, category or priority.

FR-15 — Dashboard
The system shall provide basic statistics showing the number of requests in different statuses.

FR-16 — Role-Based Access
The system shall restrict certain operations based on the user's role.
For example, an ordinary student should not be able to assign a maintenance worker to a request.

4. Non-Functional Requirements:
NFR-01 — Usability
The system should have a simple interface that can be understood by users without extensive training.

NFR-02 — Performance
Normal operations should respond within a reasonable amount of time on the prototype environment.

NFR-03 — Security
User passwords should not be stored as plain text.

NFR-04 — Validation
The system shall validate information entered by users before saving it.

NFR-05 — Maintainability
The source code should be organized into understandable components so that future changes can be made more easily.

NFR-06 — Reliability
The system should preserve maintenance requests and their history without unnecessary loss of information.

NFR-07 — Compatibility
The web prototype should work with commonly used modern web browsers.

NFR-08 — Authorization
Users should only be allowed to perform actions appropriate to their roles.

5. Business Rules:
   
1. Every maintenance request must have a creator.
2. Every request must contain a location.
3. Every request must contain a description.
4. Only authorized personnel can assign maintenance requests.
5. Maintenance workers should only update requests assigned to them.
6. A resolved request should contain appropriate resolution information.
7. Closed requests should remain available as historical records.
8. Only authorized users can change request priority.

6. Assumptions:
The project assumes that:
- Users have access to a web browser.
- Users have valid CampusFix accounts.
- Maintenance workers will have accounts in the system.
- A supervisor will be responsible for reviewing incoming requests.
- The prototype will initially run in a controlled environment.

7. Constraints
The project is a semester software engineering prototype and therefore has limited time and resources.
The first version will not attempt to implement every feature that a real university maintenance system might require.
The project will focus on demonstrating the software engineering process and a working core maintenance workflow.

8. Acceptance Criteria:
The system will be considered to meet its main requirements when:
1. A student or staff member can successfully log in.
2. A user can submit a maintenance request.
3. The request receives a unique identifier.
4. A supervisor can view and prioritize the request.
5. The request can be assigned to maintenance staff.
6. The maintenance worker can update its status.
7. Resolution information can be recorded.
8. The request can eventually be closed.
9. The request history remains available.
10. Unauthorized users cannot perform restricted operations.

9. Conclusion
The requirements in this document define the basic functionality and quality expectations for the CampusFix prototype.
They will be used as the foundation for the system design, UML models, implementation and testing in the following stages of the project.
