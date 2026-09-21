# Week 2: Process Model Justification & Project Plan

1. Selected Process Model:
For CampusFix, I have selected the Incremental Process Model.
The Incremental Model develops the system in smaller parts instead of trying to complete the whole system at once. Each increment adds more functionality to the system and can be tested before moving on to the next part.

2. Why I Chose the Incremental Model:
I chose this model because CampusFix has several different functions that can be developed separately.
For example, the first version can allow users to log in and report maintenance problems. A later increment can add request assignment and prioritization. Another increment can handle maintenance updates and closing requests.
This makes the project easier to manage because I do not have to develop every feature at the same time.
It also allows problems to be discovered earlier. If something does not work properly in one increment, it can be corrected before more functionality is added.
Another reason for choosing this model is that some requirements may become clearer after seeing the working prototype. The system can therefore be improved as development continues.

3. Proposed Increments:
   
 Increment 1 — Basic Reporting
The first increment will focus on;
- User login
- User roles
- Reporting a maintenance problem
- Recording the problem in the database
- Viewing submitted requests

Increment 2 — Triage and Assignment
The second increment will add:
- Request prioritization
- Maintenance staff assignment
- Request filtering
- Supervisor management of requests

Increment 3 — Maintenance Workflow
The third increment will add:
- Status updates
- Resolution notes
- Request history
- Closing requests

Increment 4 — Monitoring and Improvement
The final increment will add:
- Dashboard statistics
- Testing improvements
- Error correction
- Refactoring
- Documentation
- Final quality improvements

4. Project Plan:
Week| Planned Activity| Expected Evidence
1| Understand the problem and identify stakeholders| Problem statement
2| Select process model and plan the project| Model justification
3| Identify system requirements| SRS
4| Develop use cases and system design| Use-case model and architecture
5| Develop UML models and prepare prototype design| Class and sequence diagrams
6| Develop first prototype increment| Basic working prototype
7| Form/consolidate team and combine individual work| Team repository and project plan
8| Develop request triage and assignment| Updated prototype
9| Develop status and resolution workflow| Updated prototype
10| Carry out system testing and fix defects| Test results and defect records
11| Work on quality and project metrics| Quality plan and metrics
12| Implement a change request and refactor the system| Change/refactoring evidence
13| Complete technical documentation and presentation| Final documentation
14| Final testing, integration and individual defense| Final prototype and presentation

5. Project Risks
Several risks may affect the project.
Changing requirements
The requirements may change as the project develops.
Mitigation: Keep the requirements and change requests documented and review them before making major changes.
Lack of time
There may not be enough time to implement every planned feature.
Mitigation: Focus first on the main reporting and maintenance workflow before adding extra features.
Git conflicts
Different team members may modify the same files.
Mitigation: Use separate branches and pull requests and communicate before making major changes.
Database problems
Incorrect database changes could result in lost or incorrect information.
Mitigation: Test database operations and keep backups of important versions.
Unequal team participation
Some members may contribute more than others.
Mitigation: Divide tasks clearly and use Git commits, issues and pull requests to keep track of contributions.

6. Definition of Done:
A feature will be considered complete when;
1. Its requirements are understood.
2. The feature has been implemented.
3. It has been tested.
4. Any identified defects have been corrected or documented.
5. The relevant documentation has been updated.
6. The code has been committed to the repository.
7. The change has been reviewed where required.

7. Conclusion:
The Incremental Process Model provides a practical way of developing CampusFix because the system can be divided into smaller features and improved step by step.

This approach should make it easier to manage the project, test individual features and respond to changes during development.
