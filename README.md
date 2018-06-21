![CF](https://i.imgur.com/7v5ASc8.png)
# Code Fellows Project Guidelines

Welcome to Project Week! Here is a list of Code Fellows' best practices for proper Git and GitHub workflow with your project team.

<a id="top"></a>
- [Planning phase](#planning-phase)
  - [User Stories](#user-stories)
  - [Wireframes](#wireframes)
  - [Conflict Plan](#conflict-plan)
  - [Communication Plan](#communication)
  - [Project Scope](#project-scope)
- [Project Organization](#project-organization)
- [Structure and Naming](#structure-and-naming)
- [Code Style](#code-style)
- [Daily Team Workflow](#daily-team-workflow)
- [Standup](#standup)
- [Daily Goals](#daily-goals)
- [Git](#git)
- [Licensing](#licensing)
- [Documentation](#documentation)
  - [Linter](#linter)
  - [.gitignore](#gitignore)
  - [Dependencies](#dependencies)
- [Logging](#logging)
- [Deployment](#deployment)
- [Pull Requests](#pull-requests)    <a id="close-issue"></a>
- [Environments](#environments)
- [Testing](#testing)
- [API](#api)
- [Presenation Prep](#presentation-prep)
- []()

<a id="planning-phase"></a>
## Planning Phase
Before writing any code, take time to plan with your team. Make sure you are all on the same page about the goals of your application. Once you settle on an idea, prepare to pitch your idea to your instructor. 

_Why:_
> When you take the time to plan your project, you ensure that the entire team is on the same page. It can also help you identify any potential problems and how to solve them. It is easier to handle these problems now, instead of when you're in the middle of project week.

Your pitch should include the following:

### <a id="user-stories">User Stories</a>
User stories describe the features of an application based on the target audience. Each user story should map directly to a feature and should focus on who the target audience is, what they will gain from the feature, and why this feature is being included in the application. User stories follow the format of "As a ____, I want ____ so that ____."

_Why:_
> The application should focus on any of the targeted audience so you know who you are building it for a why someone would use it. User stories also help identify gaps in the planning process.

As you plan your project, define your user stories and corresponding features. If you have more features than user stories, write more user stories. If you have more user stories than features, write more features.

### <a id="wireframes">Wireframes</a>
Once you have a concept in mind, create visual represenatations of your application, called wireframes. A wireframe can be drawn on the whiteboard, on paper, or with online tools. Each page or view of your application should have its own wireframe and some pages may have multiple wireframes to illustrate change based on user interation. For example, you may have a wireframe to show how a page appears when it loads, and a second wireframe showing that same page as it will appear when a user selects an option from a drop-down menu.

_Why:_
> Wireframes provide a visualization of your final application. This is useful to make sure the team is in agreement on the general appearance of the application and can help to identify potentially unpleasant user experiences.

### <a id="conflict-plan">Conflict Plan</a>
Your team should agree on a process for handing disagreements, should they arise. It is better to have a plan in place ahead of time so you can all refer back to it if necessary. 

_Why:_
> Project week can be stressful and emotions can run high. Put together a plan ahead of time so you all know how to deal with any potential issues later.

As a team, create a Group Agreement as a markdown file to document the following:
* What will your group do when it encounters conflict?
* How will you handle members who are not adequately contributing?
* What will your process be to resolve it?
* How and when will you escalate the conflict if your attempts are unsuccessful?

### <a id="communication">Communication Plan</a>
Before beginning to write code, determine how your group will communicate with each other, both in person and online. 

_Why:_
> This is not an individual effort. Make sure everyone knows how the group will communicate with each other and that everyone feels comfortable speaking up.

Add these to your Group Agreement Some things to consider:
* How will you communicate after hours and on the weekend?
* What is your strategy for ensuring everyone's voices are heard?
* How will you ensure that you are creating a safe environment where everyone feels comfortable speaking up?

### <a id="project-scope">Project Scope</a>
Determine which features make up your minimum viable product (MVP). This should include any features you absolutely want to have in your application for presentation day. 

_Why:_
> Scope creep can be dangerous! Keeping your project within a pre-determined scope will help the group stay on task without going off on tangents and side features.

Beyond MVP, put together a list of stretch goals to tackle if you have time. During your pitch, your instructor will help you scope your project. Some features may become MVP and some may become stretch goals.

Once you are ready, find your instructor and pitch your idea.

[Back to top](#top)

<a id="project-organization"></a>
## Project Organization
Use GitHub to organize and manage your project. 

_Why:_
> The group must have a central location where they can share code in a professional manner. This will ensure that everyone's contributions are tracked appropriately and can be combined with the team's code base.

Create an organization by clicking on the plus sign in the top right corner of GitHub. Then, create your repository(ies) within the organization. All team members should be added as collaborators on the organization. 

Within the repository, click on the "Project" tab and then click the button to "Create a project". This will allow you to create a project board associated with the repository. Make several columns with meaningful names, such as "To-do", "In progress", "Under review", and "Completed". 

Populate your project with issues. Each issue should be a small item, typically linked to a feature task. As you work on an issue, assign it to yourself and move it into the "In progress" column. This will provide an easy way for everyone on the team to see the progress of each issue and know who is working on a particular issue.

_Why:_
> Issues are userful for managing small features that an individual or pair can reasonably tackle in a short period of time. The project board creates a clear visual of the team's current tasks and the current project status.

<a id="close-issue"></a>
When using GitHub issues, there is the added benefit of being able to include close issues through a commit message or a comment on a pull request (PR). For example, a commit message or comment can say "Closes #42" and the issue will automatically close when the pull request is merged. Github recognizes the following keywords to close an issue: `close`, `closes`, `closed`, `fixes`, and `fixed`. 

_Why:_
> Each PR will be associated with related issues, making it easier to look at a specific PR and identify the specific issues it addresses. 

You are welcome to use other project management tools.

[Back to top](#top)

<a id="structure-and-naming"></a>
## Structure and Naming
Before you scaffold your files within your repo, determine how you will organize your project. Your files should be organized into folders in a meaningful manner. For example, your 

<a id="code-style"></a>
## Code Style

Follow the code style you have learned throughout this course. Ensure that the team is using meaningful and descriptive names for all files, variables, function names, etc. Follow best practices with casing, spacing, and indentation. 

_Why:_
> The code base should be easy for anyone to read and understand what each line is doing. Organize your code in a way that makes it natural to read in order.

Your team should decide on standard naming conventions to use throughout the project and hold each other accountable to these standards. Do not use funny or offensive names. Write code that you will be proud to show a future employer.

The code base should also follow similar code organization from file to file. For example, all the files that affect application styling should follow similar patterns and syntax.

[Back to top](#top)

<a id="daily-team-workflow"></a>
## Daily Team Workflow

[Back to top](#top)

<a id="standup"></a>
## Standup
Every day, the instructional team with circulate to your group for a formal standup. Standup should take approximately 10 minutes per team. Some instructors will opt for a second standup later in the day.

_Why:_
> Standups give the instructional team insight into the current status of your project and the progress the team hopes to make each day.

During standup, each team member will stand up and take turns discussing three points:
> 1. What you personally accomplished yesterday
> 1. What you plan to accomplish today
> 1. Anything that is blocking you from making progress


[Back to top](#top)

<a id="daily-goals"></a>
## Daily Goals

[Back to top](#top)


<a id="git"></a>
## Git


[Back to top](#top)

<a id="licensing"></a>
## Licensing

Your repository should be initialized with an MIT license. Ensure that the resources you use are open-source and also available under an MIT or similar license. 

_Why:_
> Using resources that are not licensed for full use can lead to legal issues.


[Back to top](#top)

<a id="documentation"></a>
## Documentation


### <a id="linter">Linter</a>


### <a id="gitignore">.gitignore</a>


### <a id="dependencies">Dependencies</a>


[Back to top](#top)

<a id="logging"></a>
## Logging

[Back to top](#top)

<a id="deployment"></a>
## Deployment

[Back to top](#top)

<a id="pull-requests"></a>
## Pull Requests

[Back to top](#top)


[Back to top](#top)

<a id="environments"></a>
## Environments


[Back to top](#top)

<a id="testing"></a>
## Testing

[Back to top](#top)

<a id="api"></a>
## API

[Back to top](#top)

<a id="presentation-prep"></a>
## Presentation Prep
Your team should practice their presentation prior to

[Back to top](#top)

<a id=""></a>

[Back to top](#top)

<a id=""></a>

[Back to top](#top)

<a id=""></a>

[Back to top](#top)