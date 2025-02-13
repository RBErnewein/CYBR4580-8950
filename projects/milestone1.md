## CYBR4580/8950 Project Milestone 1: Requirements analysis and planning (Project Proposal Stage)

### Due Date
September 17th by class time

**Submit a GitHub repo link to canvas**
**Add Dr. Hale as a collaborator on your GitHub Repo**


## Overview
This project milestone tasks you with identifying project requirements, analyzing them to determine needed resources (technology and skillsets), preparing a project management plan, and packaging all of this as a project proposal. Overall, this means you will prepare a series of project management and design artifacts. Towards this goal, you will be required to submit the following by the due date:

- [Executive Project Summary](#executive-project-summary) - What are you doing and why?
  - Goals and Objectives
  - Merit of the Project
- [Proposed project timeline](#proposed-project-timeline) - When will you do it?
  - Define the tasks and expected time to completion
  - Create and submit a gantt chart
- [Project-oriented risk list](#risk-list) - What could go wrong in the project and why?
- [Project Methodology](#project-methodology) - What has been done in the literature and what is your technical plan?
- [Resources/Technology needed](#resources-needed) - What do you need to be successful?
- [First Sprint Plan](#first-sprint-plan) - Create the first plan on GitHub Kanban
- [Note about Teamwork and Group projects](#teamwork)

### Using GitHub and Markdown
For this and future projects you will submit your milestone work using GitHub (only adding the link to Canvas and Submitting a PDF copy to PURR). We will talk about this in class.

## Executive Project Summary
An executive summary should be evocative. It should capture a reader and make them want to be a part of your idea. In this milestone you will write an executive summary that defines the goals and objectives of your project in language that is easily readable and mental-image evoking. I (or anyone else) should be able to read your executive summary and instantly know a) what you are doing and b) why it is important. Executive summaries should be exciting and interesting. It is the first (and likely the only) chance for you to engage your reader and, in a real world setting, would determine if your product gets funded. An executive summary does not need technical detail to describe interesting functionality. You should mention your product by name without using phrases such as "the class", "the instructor", "project 2" etc.

### Submission materials
You should submit a summary document (in markdown format) on your GitHub project repo. Call the file README.md and place it in the top-level directory of your GitHub project.

It should contain the following:

1. A problem statement identifying relevant issues related to your bid. The problem statement might also discuss why these issues are a problematic for society, a particular industry/sector/company/agency, or a specific technology(ies).
1. Project goals and objectives in a numbered or bulleted list that you propose to undertake to address the identified problem. Clearly identify what you are doing at a high level with minimal technical detail.
1. The merit of accomplishing the project goals and objectives in terms of how it helps end users, society, or particular industries/sectors/companies/agencies.

### Grading criteria
Your summaries will be graded as follows following:

| | Meets expectations (9-10) | Some Issues (6-8) | Does not meet expectations (0-5)|
|---|---|---|---|
|Problem statement| Clearly identifies the context of the problem addressed by your project. Answers the question - Why is this an area of interest? | Problem context not clearly identified, leaves reader wondering why the project is necessary. | Problem context unclear or not identified. |
|Project goals| Project goals are clear, concise, and in a bulleted list. Efforts are clearly tied to addressing the identified problem. Goals are stated at a high level and are free of technical jargon or unnecessary detail. | Goals are not as clear, 'in the weeds,' or not directly applicable to the problem. | No goals are identified or there are severe clarity issues. |
|Project Merit | The benefits for pursing the project are clear and tied to addressing the identified problem(s). End user, societal, and industrial benefits are stated - if relevant.| Benefits and merits of the proposed work are muddled or not tied to the problem statement. | Merits are difficult to identify or missing entirely. |
|Length| Summary is of reasonable length (no longer than 1 page, not too short)| Summary is slightly too short or too long | Summary is extremely short or long. |
|Grammar, spelling, syntax | Summary is evocative and free of grammar, spelling, or syntax issues. | Summary contains a few syntax, grammar, or spelling issues. | Summary is difficult to read due to glaring grammar, syntax, or spelling issues|
|Use of markdown| Summary should render as the project homepage on your GitHub repo. It should following markdown conventions. | Doesn't perfectly follow markdown syntax or isn't rendered on the repo home page correctly. | Doesn't use markdown or isn't displayed in the repo.|

**60 points**

## Proposed project timeline
An important part of project planning is identifying tasks to be completed to address project goals and arranging those tasks in such a way that they can be completed within a (typically) fixed interval of time. In this class, that interval is the length of the semester. For milestone one, prepare an overall project timeline that identifies large tasks to be completed, estimates time of completion, and arranges those tasks chronologically over the project lifespan.

### Submission materials
You should create a gantt chart and identify *major* tasks that span the rest of the semester. I suggest using a gantt chart creation tool such as [ganttpro](https://ganttpro.com) - but you may feel free to create one in a tool of your choice (a simple table is fine). Once your chart is created, save it as an image file and display it in your README.md file, beneath your executive summary on your GitHub repo.

### Grading Criteria
Your gantt chart will be graded as follows:

| | Meets expectations (9-10) | Some Issues (6-8) | Does not meet expectations (0-5)|
|---|---|---|---|
| Identifies major tasks | Major tasks addressing your objectives (from the executive summary) are identified by name. Set of tasks is appropriate to the objectives and time frame. | The set of tasks is not scoped well (too much or too little) or they do not seem to address the objectives well. | No or few tasks are identified - or they are extremely poorly scoped. |
| Chronologically arranged | Tasks are intelligently arrayed by time. | Tasks are poorly arranged. | Tasks are extremely poorly or not arranged in time. |
| Achievable | Timeline is expectedly achievable given time frame and team size. | Timeline/task achievability is questionable. | Timeline is completely unrealistic.
| Displayed in readme file| Your gantt chart is accessible in your GitHub project repo on the same page as the executive summary | N/A | Your gantt chart is not available in your GitHub repo |

**40 points**


## Risk list
As you will probably discover, there are many things that can go wrong when working on a project. Issues with skillsets, technology, team member availability, etc, may arise as the project goes forward. As we discussed in class, there are three options available to deal with project management risks: monitor it (Watch it), mitigate it (do something about it), accept it (give up). For milestone one, you should identify the major sources of risk and what you plan to do about them. Prepare a risk list and rank them by risk level using the standard formula, i.e. `impact x likelihood`, to describe the top 5 risks that might affect your team's ability to pull off the tasks identified in your timeline and dictated by your objectives.

### Submission materials
You should prepare a risk list table and add it to your README.md file in your GitHub project repo, beneath your Gantt chart. The table should use markdown syntax such as:

```markdown
|Risk name (value)  | Impact     | Likelihood | Description |
|-------------------|------------|------------|-------------|
|Some risk (40) | 8 | 5 | Some description  |
```

to generate github-displayable tables such as:

|Risk name  | Impact     | Likelihood | Description |
|-----------|------------|------------|-------------|
|Some risk (40) | 8 | 5 | Some description  |

### Grading Criteria
Your risk list will be graded as follows:

| | Meets expectations (9-10) | Some Issues (6-8) | Does not meet expectations (0-5)|
|---|---|---|---|
|Impact| Each risk has an identified impact factor. Factor should be based on how significant the event would be towards the disruption of your project activities. | Some factors missing or unreasonable. | No factors identified or factors are completely unreasonable |
|Likelihood | Each risk has an identified likelihood factor. Factor is reasonable. | Some factors missing or unreasonable | No factors identified or factors are completely unreasonable |
|Name and description| Risk name and description are appropriate and understandable. | Some risks are unclear. | Most or all risk are unclearly described or descriptions are missing. |
|Coverage and relevance | Identified risks are relevant to the project and cover obvious potential problem areas. | Some coverage or relevance is missing. | Risks do not address obvious potential problem areas or aren't relevant.

**40 points**

## Project Methodology
Methodology is extremely important for conducting a successful project. While I am always a fan of "winging it" when it comes to day-to-day life - winging it is not an option for being successful on a team. Hence, in this class you will be required to develop a technical plan (AKA `Methodology`) to succeed. Your methodology should be grounded in scientific method and best practice. It should be based on the literature in the area you are working on and should use well-tested methods when possible.

Requirements are extremely important for conducting a successful project - of either the creative or assessment-oriented varieties. Collecting requirements about an application means understand what your end user (or what the end user of a product you are assessing) is going to do with the product. To understand requirements we often define user stories and use cases to encapsulate and represent behavior.

### Submission materials
#### Literature Review
For milestone 1, you should prepare a literature review document that surveys the various research and development work in your project area. Your literature review should identify important `keywords`, relevant `research papers`, and `the state of the art` in your area.

#### Technical Plan
Once you have examined the relevant literature, you should prepare a technical plan that outlines and defines your methodology. Important consideration should be made to ensure that your methodology uses the literature to the best extent possible. Your technical plan should provide a detailed description of exactly what and how you will do what you plan to do.

Any data collection, testing/development methods, architectures, and data analysis techniques that you wish to use should all be included in your technical plan.

### Grading Criteria
Your methodology (Lit review and Technical Plan) will be graded as follows.

#### Lit review
|| Meets expectations (27-30) | Some Issues (20-26) | Does not meet expectations (0-19)|
|---|---|---|---|
|Coverage| The literature review includes a range of topics and research relevant to the problem. | There are some areas that are not surveyed in the literature | The literature review is incomplete with respect to coverage |
|Depth| Important sources that stand out in the literature are reviewed and discussed in detail. It is clear that the team has properly reviewed the cited works. | Some important references are not properly discussed in-depth. Questions exist as to the type or application of the cited works. | Many ill-defined or poorly sourced references.|

**60 points**
#### Technical Plan
|| Meets expectations (27-30) | Some Issues (20-26) | Does not meet expectations (0-19)|
|---|---|---|---|
|Coverage| The technical plan overviews all of the areas required to be successful in the project. | Some work is not considered, but will be required. | Many missing areas of work. |
|Depth| The technical plan contains sufficient detail to understand and define exactly what will be done in the project. | Some technical details are missing or unclear. | Many technical details are missing or unclear. |
|Soundness| The technical plan is rooted in scientific method and the plan is well designed. | Some methodological issues may exist, but by and large the plan is sound. | Many issues exist in the design of the plan. |
|Scope| The technical plan is properly scoped for the duration of the class. | There are some scoping issues (too much/too little work). | Many scoping issues exist and/or the plan is unachievable. |

**120 points**
## Resources Needed
Every team needs *something* to pull off their project. Clearly identify the technologies and products involved in your project.

### Submission materials
Under your requirements section in the README.md file in your GitHub repo, clearly identify the technologies, products, and languages involved in your project. Include a table that identifies which team member will investigate each needed resource. Also include a column indicating whether or not material resources are needed from Dr. Hale.

Use the following table structure.
```markdown
|Resource  | Dr. Hale needed? | Investigating Team member | Description |
|-------------------|---------|---------------------------|-------------|
|Some resource| No | Bob | Some description  |
|e.g. PLC unit | Yes | Gary | A programmable logic controller from Siemens for investigation.|
```

This will generate a table of the form:

|Resource  | Dr. Hale needed? | Investigating Team member | Description |
|-------------------|---------|---------------------------|-------------|
|Some resource| No | Bob | Some description  |
|e.g. PLC unit | Yes | Gary | A programmable logic controller from Siemens for investigation.|

### Grading Criteria
You will be graded as follows:

|| Meets expectations (9-10) | Some Issues (6-8) | Does not meet expectations (0-5)|
|---|---|---|---|
|Coverage| A reasonable set of resources are listed that are appropriate to your project.|Some missing critical resources that are needed but not listed. | Many critical resources are needed, but not listed.|
|Conforms to structure| Entries follow tabular format specified. Each resource has an assigned team member investigating it. | Some issues following structure. | Table not formatted or many issues.|

**20 points**
## First Sprint Plan
This milestone represents the first step forward in your capstone project. As part of that effort, you need to plan your first real sprint.

### Submission materials
This part of the milestone is strictly captured by GitHub Projects (its a `Kanban` board technology like Trello). In your Kanban board, create a board following the structure discussed in class (see Lecture 4). Use this structure to identify the tasks that you will tackle in your first sprint. Put those tasks in the **Sprint To-do** category.

### Grading Criteria
No fancy grading rubric here. You will receive points for participating (as measured by the activity flow) in GitHub. If you are not taking tasks or helping to manage the project managment space, chances are you won't get these points.

**20 points**

## Presentation
You will be expected to present your Milestone 1 proposal to the class. It is important that you use this time to inform your classmates and get feedback. Things to be considered are 1) conveying a sense of interest and excitement about your project 2) cool product demos, and 3) interesting findings of conducting your projects.

### Submission Materials
Submit your slides to Dr. Hale on slack by posting and pinning them in your team slack channel.

### Grading Criteria
You will be graded by a presentation rubric on canvas.

**Total 70 points.**

## Teamwork
Lastly, it is important that you realize you are working on a TEAM (except for the few of you that are soloing). I will say now, that your grade is dependent on your participation. I will not allow individuals to sluff off on a team. Your grade is therefore based partly on a *participation factor*. Essentially if you don't participate (and trust me We will know) - you will not get all of the team points on your project grade.

Your final grade on the milestone is computed as follows:
**team_grade** * **participation_factor** = **individual_grade**

**participation_factor** is a number from .4 to 1 that is based on four measured participation factors:

1. Contribution to the GitHub repo
1. Activity in the slack channel for your project
1. Activity on GitHub Projects
1. In-class participation and participation in team meetings.
1. Team evaluations

If you do your work and participate, you will get the full team poitns (**participation_factor**=1), if you don't, you will get as little as 40% of the team points. This means that you can **FAIL** even if your team succeeds. - So don't sluff off.


## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">CYBER4580 and related works</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://faculty.ist.unomaha.edu/mlhale" property="cc:attributionName" rel="cc:attributionURL">Matt Hale</a> are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
