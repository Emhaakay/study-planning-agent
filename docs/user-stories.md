# User Stories 
 
## US-01 Generate a weekly study plan 
As a student, I want the agent to generate a 7-day plan from my assignments, so that I can focus on the most urgent and important work first. 
Related requirements: FR-02, FR-04, NFR-03, AG-01 

## US-02
As a student, I want to see why a task was scheduled early, so that I can judge whether the suggestion makes sense. 
Related requirements: FR-02, FR-04, NFR-03, AG-01 

## US-03
As a student, I want to regenerate the plan after changing a deadline, so that the plan reflects current information. 
Related requirements: FR-02, FR-04, NFR-03, AG-01 

## US-04
As an IT administrator, I want external integrations to use minimum permissions, so that unnecessary account access is avoided. 
Related requirements: FR-02, FR-04, NFR-03, AG-01 


### Acceptance criteria 
AC-01 
Given the student has entered three assignments with valid deadlines, 
When the student generates a weekly plan, 
Then all three assignments appear in the 7-day plan. 
 
AC-02 
Given two assignments have different deadlines, 
When the plan is generated, 
Then the system shows a visible reason for the suggested ordering. 
 
AC-03 
Given one assignment has no deadline, 
When the student requests a plan, 
Then the agent asks for the missing deadline instead of inventing one. 