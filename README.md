# Quality Assurance (QA

Created: September 18, 2023 4:59 AM
Tags: Article, Notes
📝 Homework: Research about big tech companies (https://www.notion.so/Research-about-big-tech-companies-15eeee77e46743399853dd8b6237e918?pvs=21)

![https://blog.qasource.com/hubfs/top-10-best-software-QA-testing-companies-in-USA-for-2023.png](https://blog.qasource.com/hubfs/top-10-best-software-QA-testing-companies-in-USA-for-2023.png)

---

# **Software Requirements: Requirements Analysis**

Requirements are a specification of what should be implemented. They are descriptions of how the system should behave, or of a system property or attribute

### User Story vs User Cases

**User story is a simplified form of many users interacting with a software.** **Use cases are very specific in relation to user stories**. They describe specific user actions with any system.

---

### Requirements testing:

• Unaccounted for dependencies
• Testability
• Alternative flows in the business scenarios
• Check that there are no inconsistencies
• General logic about users’ feelings

---

### What do we want from the analysis?

• Understanding business processes and the meaning of the user story
• Acceptance criteria
• Custom scripts
• Dependency analysis and impact on existing functionality

---

### Smart Requirements

Smart requirements are specific, measurable, achievable, relevant, and time-bound. They help ensure that project goals and objectives are well-defined and attainable. Here's a brief explanation of each component:

1. Specific: Requirements should be clear and precise, leaving no room for ambiguity. They should answer the who, what, when, where, and why of a project.
2. Measurable: Requirements should be quantifiable, allowing for objective assessment of success or completion. This often involves using metrics or criteria to evaluate progress.
3. Achievable: Requirements should be realistic and attainable within the constraints of the project, including time, resources, and budget.
4. Relevant: Requirements should directly contribute to the project's goals and objectives, ensuring that they are worthwhile and aligned with the project's purpose.
5. Time-bound: Requirements should have a defined timeframe or deadline, helping to manage project schedules and priorities effectively.

By adhering to SMART requirements, project managers and stakeholders can enhance project clarity, control, and success.

---

### Use Flow Diagram

A flow diagram is a visual representation of a process or system that uses symbols and arrows to illustrate the sequence of steps or components. It helps in understanding, analyzing, and communicating complex processes, making information more accessible and structured.

### Prototypes:

Prototypes are simplified, early versions of a product or system used to visualize, test, and refine its design and functionality. They help stakeholders better understand the final product and identify potential improvements or issues before full-scale development.

### Work Breakdown Structure (WBS):

A Work Breakdown Structure is a hierarchical diagram that breaks a project into smaller, manageable tasks or work packages. It provides a structured framework for organizing and planning project activities, making it easier to assign responsibilities, estimate resources, and track progress.

---

## Key Takeaways:

- Main two types of requirements: use cases and user stories
- The whole development team works with the requirements
- There are some requirements how the "ideal requirement" should look (SMART approach)
- Requirements testing approaches: User flow diagram, Prototypes and Work Breakdown Structure

---

# Test Types and Levels

- Development Levels:
    
    Development levels represent different stages in the creation of a product or system. These stages typically include design, coding, testing, and integration. Each level focuses on specific tasks and goals to gradually build and refine the final product.
    

---

- Test Levels:
    
    Test levels refer to distinct phases of the testing process during software development. They range from unit testing (testing individual components) to system testing (testing the entire system's functionality). Test levels ensure comprehensive evaluation of the product's quality and performance at various stages of development.
    

![Screenshot 2023-10-31 at 7.19.06 AM.png](Quality%20Assurance%20(QA%20dff4c6fbe7f1473281f4acf81b8540b2/Screenshot_2023-10-31_at_7.19.06_AM.png)

A test type is a specific category of testing that focuses on checking different aspects of software quality, including:

1. ***Functional quality***, which looks at things like correctness and completeness. (e.g *What* does the system do? )
2. ***Non-functional quality***, which assesses aspects like reliability, performance, security, compatibility, and usability. (e.g *How well* does the system work?)
3. ***Structural or architectural correctness***, ensuring the software is built according to specifications. (e.g How the system works?)
4. ***Testing the impact of changes***, which includes confirming fixes and checking for unintended consequences (regression testing). (Does the system work after a change?)

---

### Functional & Non-Functional Testing

- ***Functional Testing:***
Functional testing assesses a system's functions, checking if it performs as expected. These functions are often described in documents like business requirements, user stories, or specifications. It evaluates "what" the system should do and can be done at various test levels. Black-box techniques are often used to create test cases, especially when testing software behavior. It may require domain-specific knowledge, like understanding the business problem the software solves.
- ***Non-Functional:***
Non-functional testing focuses on characteristics like usability, performance, and security. It evaluates "how well" the system behaves and is crucial at all test levels, preferably early in the process to catch defects before they become problematic. **Black-box** techniques are useful for creating test cases, such as using boundary value analysis for performance tests. You can measure the thoroughness of non-functional testing through non-functional coverage, ensuring you've addressed aspects like device compatibility for mobile applications. Late discovery of non-functional defects can be risky for a project's success.

### Functional vs. Non-functional Testing:

Functional testing checks what the software does, like its features and functions. Non-functional testing checks how it does it. Here are some key non-functional aspects:

- Reliability: Ensures the software works consistently and reliably.
- Performance: Evaluates speed, responsiveness, and efficiency.
- Usability: Examines user-friendliness and ease of use.
- Maintainability: Assesses how easy it is to maintain and update the software.
- Security: Focuses on safeguarding against vulnerabilities and threats.
- Compatibility: Checks if the software works well with different systems and browsers.
- Portability: Ensures the software can run on various platforms and devices.

---

### Testing Types Based on System Access:

1. Black Box Testing:
    - Based on requirements and specified behavior.
    - Independent of the software's internal structure.
    - Test cases remain useful even if the implementation changes, as long as the required behavior stays the same.
    - Relies heavily on well-defined requirements.
    - Thoroughness measured by covering all stated requirements with test scenarios.
2. White Box Testing:
    - Derives tests based on the system's internal structure, including code, architecture, workflows, and data flows.
    - Thoroughness measured through structural coverage, which assesses the extent of exercised structural elements.
    - Can focus on component code coverage or system architecture, depending on the testing level.
    - Involves knowledge of code, data storage, and the use of coverage tools.
3. Gray Box Testing:
    - Tester has partial knowledge of the system's internal structure, including access to documentation of data structures and algorithms.
    - Involves intelligent test scenario handling, like data types, communication protocols, and exceptions.
    - Requires both high-level and detailed documentation of the application.
    - Well-suited for web applications and functional/business domain testing.

---

### Typical Test Objects:

1. Component Testing:
    - Focuses on individual parts like components, units, or modules.
    - Involves testing code and data structures, classes, and database modules.
    - Typically conducted by the developer who wrote the code.
2. Integration Testing:
    - Tests the interaction of subsystems, databases, infrastructure, interfaces, APIs, and micro-services.
    - Ensures different components work together as a unified system.
3. System Testing:
    - Evaluates complete applications, hardware/software systems, operating systems, and the entire "system under test" (SUT).
    - Includes system configuration and configuration data.
4. Acceptance Testing:
    - Validates the SUT in its entirety.
    - Assesses business processes for a fully integrated system.
    - Considers recovery systems and hot sites for business continuity and disaster recovery testing.
    - Examines operational and maintenance processes.

---

## Key Takeaways

1. Each test level is an instance of the test process, consisting of
activities performed in relation to software at a given level of
development, from individual units or components to complete
systems or, where applicable, systems of systems. Test levels
are related to other activities within the software development
lifecycle.
2. There are various test types and classifications depending on
the goal of the testing.
3. Every test type can be performed at any test level.
4. It is important to run applicable test types at each level,
especially at the earliest level where the test type occurs.

---

# **Test Documentation**

- Test documentation includes various documents created before and during testing.
- It describes test coverage, execution, responsible parties, lists essentials, tracks issues, and more.
- Provides a central source for all testing information, ensuring clarity and organization.
- Helps turn informal processes into formal and structured ones.

                                            ***Types of Test Documentation***

![Screenshot 2023-10-31 at 7.57.30 AM.png](Quality%20Assurance%20(QA%20dff4c6fbe7f1473281f4acf81b8540b2/Screenshot_2023-10-31_at_7.57.30_AM.png)

- Test Policy:
    - A high-level document outlining testing principles, methods, and goals.
    - Collaboratively created by senior members of the test management team and stakeholder managers.
    - Goals include justifying the cost of quality, defining test objectives, measuring test efficiency, summarizing testing processes, and enhancing testing within the organization.
- Test Strategy:
    - A planning document detailing the scope, approach, resources, and schedule for testing activities.
    - Format and inclusion can vary among organizations, with some incorporating it within the test plan.
- Test Plan:
    - High-level document identifying test levels, features to be tested, and key information.
    - Typically includes test schedule, priorities, regression test approach, roles, environment requirements, tools, risks, entry/exit criteria, and more.
    
- Test Scenarios:
    - Items or events in software that can be verified by one or more test cases.
    - Describes user-system interactions, including actors, preconditions, triggers, expected results, success scenarios, alternative paths, and post conditions.
    - Based on business requirements, system requirements, and assumptions.
    
- Test Cases:
    - A set of actions verifying specific application features based on test scenarios.
    - Include preconditions, test data, step-by-step instructions with expected results, priority, status, and additional information.
- Checklist:
    - Simplified test cases focusing on covering all possible user actions within a functionality.
    - Provide shorthand verifications, expected results, and status.
    - Useful for quick and efficient testing, but may lack detailed instructions for complex applications.
- Bug Report:
    - Contains comprehensive information about a bug, including its description, severity, priority, and steps to reproduce.
    - Includes summary, version/build/environment, status, preconditions, actual and expected results, and attachments like logs and screenshots.
    - A well-documented bug report facilitates faster defect resolution.

---

## Key Takeaways

1. Test documentation is an important part of a QA’s daily activities as it helps to keep things in order. 
2. There are different levels of test documentation.
3. The main requirement of test documentation is to keep it simple and sufficient. Make sure it has all the necessary info and is not overloaded with unnecessary details.

---

# **Test Design Techniques**

***Test Design and Test Design Techniques:*** 

- Test Design
    - The process of transforming general testing objectives into tangible test conditions and test cases.
- Test Design Technique
    - A procedure used to derive and/or select test cases.

---

***Test design goals:*** 

- Provide optimal test coverage of the application:
    1. Tests should cover all functionality
    2. Tests should be minimal enough

---

***Test techniques are classified as:*** 

- Black-box → *Black-box testing analyzes requirements and system behavior without delving into its internal structure, making it suitable for both functional and non-functional testing.*
- White-box → *White-box testing analyzes a system's internal structure, including its code, architecture, and design, in contrast to black-box testing, which looks at system behavior.*
- Experience-based → *Experience-based test techniques use collective knowledge from developers, testers, and users to design and perform tests, often alongside black-box and white-box techniques.*

### Black-box Test Design Techniques:

### 1. Equivalence Partitioning

     *Equivalence Partitioning* is a black-box testing method that creates test cases to represent different input or output groups, assuming the system behaves the same within each group, based on the specification. The goal is to cover each group at least once in the test cases (test at least one value from each class). It’s important to test valid and invalid equivalence classes.

     *Equivalence Partitioning* involves testing both **valid** and **invalid** values. Valid values should be accepted, forming valid equivalence partitions, while invalid values should be rejected, creating invalid equivalence partitions. Starting with valid data is a common practice in this method. It focuses on grouping similar data into equivalence classes, which include both valid and invalid values.

***Algorithm for using the technique:***

1. Define equivalence classes.
2. Pick a representative from each class.
3. Perform tests for each equivalence class.

---

### 2. Boundary Values

    ***Boundary Value Analysis*** is a black-box testing technique that focuses on testing values at the boundaries of equivalence partitions. Boundary values are the values right at the edge of these partitions. 

    The algorithm involves defining the range of values (an equivalence class), identifying the boundary values, creating three test cases for each boundary, and executing the tests for these boundary values. The goal is to test the system's behavior at the edges, where issues often arise.

---

### 3. Pairwise Testing

    ***Pairwise Testing*** is a black-box testing technique designed to efficiently test all possible combinations of input parameters in pairs. Instead of testing all possible combinations for all values of the variables, it focuses on testing all pairs of variables. This method significantly reduces the number of test cases needed while still ensuring comprehensive coverage. It's especially useful when dealing with a large number of possible combinations.

---

### 4. Decision Table Testing

    ***Decision Table Testing*** is a *black-box* testing technique where test cases are designed to execute combinations of inputs and stimuli specified in a decision table. This method is useful for recording complex business rules, ensuring that all possible condition combinations have been considered, and easily identifying missed conditions.

- **Conditions:** Represent input conditions and can be Boolean or have multiple values.
- **Actions:** Define processes to be executed based on input parameter combinations.
- **Rules:** Describe unique combinations of conditions leading to specific actions.

Decision table testing aims to achieve 100% coverage of all condition combinations, helping find gaps or requirements' lack of clarity.

---

### 5. State Transition Testing

    ***State Transition Testing*** is a black-box testing technique that employs a state transition diagram or state table to create test cases. These test cases evaluate if a system successfully executes valid transitions while preventing invalid transitions.

- **State Transition:** It represents a change from one state to another in a component or system.

State transition testing is useful when a system has states and needs to respond to real-time events from outside the system. It's not applicable when the system lacks states or doesn't require responses to external real-time events.

### Key Takeaways

1. The test design's goals are to provide optimal test coverage of the application.
2. Test techniques are classified as *Black-box, White-box, and Experience-based.*
3. Main Black-box test design techniques:
    - 1. *Equivalence partitioning* — test cases are designed to execute representatives from equivalence partitions.
    - *2. Boundary value analysis* — test cases are designed based on boundary values of equivalence partitions.
    - *3. Pairwise testing* — test cases are designed to execute all possible discrete combinations of each pair of input parameters.
    - 4. *Decision Table Testing*: Test cases are created to execute combinations of inputs and stimuli as specified in a decision table.
    - 5. *State Transition Testing:* Test cases are based on state transition diagrams or state tables and typically involve sequences of events leading to state changes (and possible actions). A single test case can cover multiple state transitions. These techniques focus on testing different aspects of a system's behavior without delving into its internal structure.

---

# Defects and Bug Tracking

### 1. Mistake, Defect, and Failure in Software:

- **Mistake:** A human error or oversight in the software development process.
- **Defect (Bug):** An error, flaw, or fault in the software that causes it to produce an incorrect or unexpected result, or behave in unintended ways. It's an inconsistency between actual and expected behavior.
- **Failure:** The software's inability to meet its intended functionality, often caused by defects.

---

***The First Computer "Bug":***
     On September 9, 1947, Grace Hopper encountered the first computer bug. It was a physical moth stuck between a relay in the Harvard Mark II computer, causing a malfunction. Hopper recorded this incident as the "First actual case of a bug being found." This term, "bug," has since become synonymous with software defects.

---

### 2. Bug Report

    A bug report is a document that highlights any flaw in a component or system that can disrupt its intended functionality. The purposes of creating a bug report are:

1. **Notification:** It informs the development team and other relevant individuals with a detailed description of the problem.
2. **Prioritizing:** It helps define the potential impact on the project and the desired time for elimination.
3. **Assistance for the Fix:** A well-structured bug report, which includes an analysis of the problem and possible root causes, can serve as the first step in resolving the bug.

***General Tips for Bug Reports:***

- Report all identified bugs.
- Write the report clearly and politely.
- Focus on one problem per issue for easier processing.
- Provide objective facts about the bug rather than speculative explanations.
- Reproduce the bug before reporting to ensure clarity.
- Test for the same defect in similar modules, as developers often reuse code across multiple areas, increasing the likelihood of the issue occurring in other parts.

---

***Bug Report Attributes:***

- **Defect ID:** A unique identification number for the bug.
- **Summary:** A concise description of the bug.
- **Project:** The name of the project the bug relates to.
- **Affected Version:** The version in which the bug was discovered.
- **Fix Version:** The version in which the bug is expected to be resolved.
- **Reported By:** The individual who reported the bug.
- **Assigned To:** The person responsible for fixing the bug.
- **Status:** Indicates the current status of the defect (e.g., Open, In Progress, Testing, Closed, Reopened, etc.).
- **Severity:** Reflects the impact of the defect on the application.
- **Priority:** Indicates how urgently the bug needs to be addressed.
- **Steps to reproduce (STR)** — steps that need to be performed to reproduce the bug
- **Actual result** — what happens after the STR are executed
- **Expected result** — what should happen after the STR are executed
- **Preconditions** - Special conditions that need to be performed before attempting to reproduce the bug
- **Attachments** - Screenshots, videos, logs, and files which will help to understand the root cause

---

***Tips for Writing Bug Descriptions:***

1. **Clarity is Key:** Ensure your bug report is clear and concise, allowing others to consistently reproduce the issue.
2. **Reproduce the Bug:** Find the precise steps to consistently reproduce the bug.
3. **Be Specific:** Avoid vague phrases like "I clicked on the link." Instead, use specific actions like "Click the 'Login' link."
4. **Include Preconditions:** If necessary, add any prerequisites or conditions that are relevant to reproducing the bug.
5. **Test Your Own Instructions:** Pretend you are someone else following your instructions to validate their clarity.
6. **Actual vs. Expected:** After providing steps, detail what actually happened (actual result) and what you expected to happen (expected result).
7. **Provide System Details:** Specify the operating system, web browser, device, or any other relevant environmental information. This aids in isolating the problem and fixing it.

---

***Tips to Create Attachments:***

1. **Screenshots** →  *Highlight the area that contains the bug. If you need to show a multiple places you can use enumeration.*
2. **Text Files** → *Attachments should aid developers in issue resolution, including log files, input/output data in standard formats, and error messages, while avoiding proprietary file types like .docx and ensuring they contain relevant bug-related information.*
3. **Video** → *Video evidence should align with the reported steps, be trimmed to show only the bug, and be provided when steps are complex, with attention to file size limitations in bug-tracking systems.*

---

### 3. Severity vs. Priority

    So, to put it simply, severity is about how bad a problem is, and priority is about how quickly we need to fix it. We use these two things to decide which problems to fix first when we're testing and making things better.

***Severity Degree of Impact:***

1. Blocker 
2. Critical
3. Major
4. Minor
5. Trivial

***Priority Degree of urgency:***

1. High
2. Medium
3. Low

---

### 4. Bug Life Cycle

![Screenshot 2023-10-31 at 11.01.28 AM.png](Quality%20Assurance%20(QA%20dff4c6fbe7f1473281f4acf81b8540b2/Screenshot_2023-10-31_at_11.01.28_AM.png)

### 5. Bug Report Resolution:

    The Resolution field is employed to indicate how issues are resolved. Potential resolutions encompass:

- **Fixed:** The bug was rectified by modifying the source code.
- **Won't Fix:** A decision was made not to address the bug.
- **Can't Reproduce:** The bug cannot be replicated.
- **By Design:** The person reporting the bug had a misconception about the software's intended operation, and it is functioning correctly.
- **External:** The bug results from an external factor unrelated to the software.
- **Duplicate:** The bug has already been reported.

---

### 6. Bug Tracking System:

    A system for receiving and filing bugs reported in a software project and tracking those bugs until they are fixed. (e.g JIRA, Mantins)

---

## Key Takeaways

1. A bug report is a detailed instruction how to reproduce a bug
2. A bug report should always list the expected and actual results
3. A bug report is an instruction on how to reproduce a bug
4. A bug always has expected and actual results
5. Severity is the degree of impact to the system
6.  Priority is the level of importance
7. The main workflow for bugs is: New, Assigned, Resolved, Closed
8.  Bug Tracking Systems all provide the same basic functionality