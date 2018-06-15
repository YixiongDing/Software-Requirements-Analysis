# Software Requirements Analysis Notes

Summary is wriiten by Yixiong Ding  
The University of Melbourne  
June, 2018   
_ _ _

## Interviews
_ _ _

### Communication principles
1. Listen to the client
2. Prepare yourself
3. Have a facilitator
4. Best face to face
5. Take notes
6. Collaboration
7. Stay focused
8. Always move on
9. Not a contest

### Types of interviews
1. Structured interviews
    - More focused
2. Unstructured interviews
    - Might identify unexpected issues
3. Semi-structured interviews

### General interviewing protocol
1. Identify candidate
    - What data are you after?
    - Need to understand the organisation
2. Plan interview
    - What do you want to get out of it?
    - Learn about the domain and terminology
3. Conduct interview
    - Follow up answers
    - Ask questions and record answers
4. Analyse results
    - And go back to interviewee to get feedback/validation

### Interviewing guidelines
1. Identify complete set of stakeholders
2. Establish rapport
3. Friend not foe
4. Focus on the interviewee work and problems
5. Keep open ended questions for the end
6. Follow up interesting answers
7. Ask the ‘why’ of pre-established solutions
8. Avoid questions
    - Opinionated or biased
    - Imply an answer
    - You know the answer
    - Silly – answered by previous research
9. Look at the data soon before you forget non-verbal factors
10. Keep people in the loop
11. Never say “usually”
12. Encourage stories
13. Find inconsistencies
14. Non-verbal cues
15. Don’t fear silence

_ _ _
## Software Processes
_ _ _

### Software projects
1. Software projects replace existing systems (even if a manual one)
2. The system-as-is vs the system-to-be
    - Often the system-to-be will interact with other software, people and processes
3. “Easy” vs “hard” problem domains 
    - Get to know the problem domain 
    - Share the client's lexicon

### Why building a system?
1. Students often not exposed to the Business Brief
2. Motivation of the system-to-be
    - Why is it necessary?
    - Goals?
    - How does it fit in the business strategy?
3. Define the boundaries software/system 
    - System > Software 
4. Scope and scope creep 
    - Prioritise!

### A classic waterfall process
<img src="classic_waterfall.png" alt="550" width="550">

### Requirements Engineering
1. Finding out what the client wants
2. Foundation for rest of development
3. Requirements engineering
    - Repeatable process of gathering and refining requirements
4. Harder than it looks like
    - Communication with client essential

### A classic RE process
1. Inception
    - Basic understanding of the problem, identify the people who want the solution, the nature of the solution
2. Elicitation
    - What is to be accomplished, how the system fits into the needs of the business, and how the system will be used on a day-to-day basis
3. Specification/Modelling
    - Refining the elicited data as requirements models
4. Negotiation
    - Scoping with client, bringing together various viewpoints, resolving conflicting requirements, prioritizing requirements
5. Validation
    - Ensuring the specification is correct, unambiguous, and free of inconsistencies. Validate with stakeholders to establish baseline
6. Requirementsmanagement
    - Maintain changes in requirements throughout the lifecycle of the system

### An agile process
<img src="agile_process.png" alt="550" width="550">

### An agile inception
1. Helps reach alignment and set expectations
2. Team gets ready to start a project
3. Typically a 1 or 2 day meeting
4. Involves dev team and clients
5. Elements:
    - Vision and goals
        - Motivation of the project and main goals
    - Non-goals
        - What’s out of scope
    - Risks
        - Brainstorm, prioritise and revisit
    - Roles / personas
    - Activities / workflows
    - Stories
        - Later decomposed into tasks
    - Estimations
    - Priorities
    - Retrospective

_ _ _
## Goal modelling
_ _ _

### Models
1.  Abstraction from real world
    - Support the understanding of some aspect
2. They represent information needed for the development
    - Do not over-elaborate
    - Stop when there is a base for design
3.  Support discussion between stakeholders
4. Empowering
    - Brings you closer to the final product

### Do, be, feel lists
1. One efficient way of eliciting requirements
    - Complementary to interviews
2.  Structured form of brainstorming
3. A workshop activity involving many stakeholders
    - Can capture viewpoints or partial views of the problem

#### Preparation
 1. Participants
    - Facilitator: run the activity
    - Scribe: write down participant’s suggestions
    - Range of stakeholders involved in the problem
2. Resources
    - Markers (3 different colours if possible)
    - Whiteboard or similar – 15 to 30 minutes

#### Introducing the activity
1. Explain purpose of the session(project purpose)
2. Explain the 4 categories
    1. Do
        - What should the system do?
    2. Be 
        - How should it be done? Constraints on features
    3. Feel
        - Emotional (or social) considerations or concerns regarding features
    4. Who
        - Types of stakeholders involved in the system

#### Populating the lists
1. Ask the audience for contributions
2. Write down ideas under the right category 
    - Different colours for different categories?
3. No strict order
4. Brainstorming principles, e.g. no filtering out

#### Prioritising
1. Optionally end the activity extracting priorities
    - Longer session
2. Many different techniques
    - Pick a lean technique
3. Do it now or later
    - If later, your ideas will be clearer
    - If now, stakeholders have the discussion fresh and are together to discuss inconsistent perceptions

#### Close the activity
1.  Record the results
    - Photo? Counting dots?
2. Thank participants
3. Explain the process
    - Analysis of result
    - Return to them for clarification and feedback

### Goal model
1. Visual representation of goals and involved actors
2. In traditional software engineering
    - Semi-formal specification
    - Used to derive other lower level models leading to design
3. Our purpose
    - Conversation starter between client and dev team
    - Represents shared understanding of the problem
    - Notation easy to understand for non-technical stakeholders
4. Two possible levels
    1. Motivate the project, describe the problem
    2. Describe general aspects of the sought system (non-technical!)
5. 1 and 2 combined in one diagram in some cases