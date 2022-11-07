# Information on Ticket Analysis

## Setup & General info:

### Markup Language

- So, for adding the description in the ticket there we use Mark Up language
    - To know more about this you can visit [Basic writing and formatting syntax - GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
    - Other wise you can use UI elements present already:
    
    ![Untitled](Information%20on%20Ticket%20Analysis%20e73ca6c51b0845d6b7ebd12ee72db45a/Untitled.png)
    

### Markup text editor

- Will suggest to **use mark up text editor** which can be helpful as our tickets use the same.
- To download mark Text click [here](https://github.com/marktext/marktext#download-and-installation). It’s one of the mark up text editor
- **Alternative to Mark Text**: [**Obsidian](https://obsidian.md/), [Notion](https://www.notion.so/)** and many more.
- Currently application which I use is **obsidian**.

## Points which should be covered in the analysis:

### Checkboxes (Things to check while doing or after the analysis)

Brainstorming should cover all the below points:

- [ ]  Why?
- [ ]  What?
- [ ]  How?
- [ ]  Security Concerns.
- [ ]  Time analysis (Story points)
- [ ]  Discuss with respective UI/Backend person and above points should then be noted commonly.
- [ ]  Note down questions (if any) regarding the ticket.
- [ ]  Call with LEAD and Module Lead to do brainstorm of ticket together.
- [ ]  Verify the analysis done by you and respective UI/Backend person.
- [ ]  Ask and raise question/doubts which can be blocker or not clearly mentioned in ticket.
- [ ]  If not cleared in brainstorming session then verify and get confirmation/answers on those points from Clients.
- [ ]  Put the finalized analysis in Analysis subtask of ticket.
- [ ]  Create subtasks (UI, Backend)

> Each of the subtask should be of 2 hours only, If its taking more time time then we have to break it down further.
> 
- [ ]  Create and Unit Testing subtask and add the Cases which will need the testing.

### Checkbox points explained in detail

- Why?
    - Why this ticket was created?
    - Why this changes are needed?
    - Why we didn't existing functionality (if any similar functionality is present)
- What?
    - What changes would be needed in a generalized way?
- How?
    - UI changes
        - This should contain UI changes as subpoint with the required changes (in list format).
        - With Controller name, file name, project name, function name whichever is relavent in the case.
        - You can add mockups or screenshots with pointer which would help understand the changes more.
    - Backend changes
        - This should contain all the backend changes in list format which should also cover changes in Database (Table/Column) & Model changes among the code changes
        - With Controller name, Service name, file name, project name, function name whichever is relevant in the case.
        - You can also add new API names, property names, so that while implementing it will be useful for UI as well as backend developer.
- Security Concerns.
    - This should contain any point which should be checked or paid attention too.
    - This point should be noted and revisited after the completion of the development of ticket.
    - For example, authentication for API, showing sensitive on UI without masking, etc.
- You can add an additional point in How section if needed like calculation, or SDK information, etc.
- **To answer this we should:**
    - Check description of the ticket.
    - Check tickets linked to the our ticket (if any)
    - Check the functionality mentioned.
    - Check KT document (if any)
    - Check the code in project or similar functionality (if any)
    - Discuss with person who developed ot worked on it (if available)
    - Discuss with the Module Lead (if available)