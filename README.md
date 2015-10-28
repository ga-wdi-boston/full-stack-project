# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project #2: Building A  Full-Stack Application

## OVERVIEW

This second project will be your first foray into **building a full-stack application.** You'll be **building your first real back-end app, with a front-end to match,** which means you'll learn about what it takes to build an API & use it.

At a high level, here are our goals for you in this project:
- **Build a single-page application (SPA)** with **basic user authentication** that interacts with a **custom API that you build**
- Build an app that can **create, read, update, and delete data** in a SQL database
- Learn to **create user stories and wireframes** (before writing code) as part of planning out your app.
- Learn to **confidently present your work** to a technical audience (5-10 minute presentation)

>**You will be working individually for this project, and you'll be designing the app yourself. Remember to keep things small – scope creep/feature creep is a huge potential pitfall for any project!**

---

## DELIVERABLES

When you present your project, you must hand in the following things

- A **working full-stack application, built by you**, hosted somewhere on the internet (see Technical Requirements, below)
- Two **Github repos** (one for your front-end and one for your back-end), with frequent commits dating back to the very beginning of the project. Each repo will need a **README.md file** with a link to the other repo. Your front-end repo's README should also have
  - An **explanation** of the what the app does and how it works, the approach taken in building it, and any unsolved problems that you hit.
  - **User stories** written for your app.
  - At least one **wireframe** (or a link to one) that you've created to plan out your app.
  - A **link** to the live application.

#### Technical Requirements

In order to get a satisfactory score, your app must:

* Have an **API** that is securely accessible by your browser app, built using frameworks covered in class.
* Create **at least 4 RESTful routes** for handling GET, POST, PUT/PATCH, and DELETE requests.
* **Utilize an ORM** to create a database table structure and interact with data.
* **Use a front-end Javascript app** to communicate with your API (both read and write) and render data that it receives in the browser.
* Have **semantically clean HTML and CSS**
* Be **deployed online**, so that it is accessible to the public

##### Stretch Goals

Once (and only once) you've satisfied the core requirements, here are some additional goals that you can shoot for:
* Incorporate Bootstrap, Handlebars, or some other front-end tool.
* Interact with third-party APIs and integrate them into your app.
* Put some extra thought and effort into visual and UI design.

---
## FEEDBACK

Your instructors will give you a total score on your project as an aggregate across all feedback categories:

  Score | Expectations
  ----- | ------------
  **0** | _Does not meet expectations._
  **1** | _Meets expectactions, good job!_
  **2** | _Exceeds expectations, you magnificent creature, you!_

This will serve as a helpful overall gauge of whether you met the project goals. But more important than your overall score is your feedback, particularly in individual categories - this will help you identify where to focus your efforts for future projects.

Below are specifics on each category, along with examples of what `0`, `1`, or `2` might look like.

### Workflow
##### __Planning__
Did you complete user stories and wireframes before you started writing code? Did you create a schedule for yourself to keep your project on track?

| Score | Description |
|:-----:|:------------|
| 0 | No planning documents present. |
| 1 | Basic planning documents (wireframes and data model) |
| 2 | Clear, detailed planning materials that make it easy for someone to follow the entire flow of the project. |
##### __Source Control__
Did you use source control to keep track of changes in your project and make regular 'save points' for yourself?

| Score | Description |
|:-----:|:------------|
| 0 | Large, infrequent commits containing work on multiple disparate features. |
| 1 | Small, regular commits that reasonably divide up the work that was done. |
| 2 | Sophisticated use of branching and merging for managing different features. |

### Deliverables
##### __Technical Requirements__
Does your project meet all the technical requirements outlined above? Does it run?

| Score | Description |
|:-----:|:------------|
| 0 | App does not run on localhost, or runs but is missing significant features specified above. |
| 1 | App meets most core requirements and has been deployed (in some form) to Heroku. |
| 2 | App meets __all__ core requirements _and_ acheives some stretch goals. |
##### __Software Design/Problem Solving__
How did you break up the functionality of your application? Do the solutions you came up with make sense, from the perspective of industry best practices? How well can you defend the choices you've made?

| Score | Description |
|:-----:|:------------|
| 0 | Little to no separation of concerns on the front-end. Poor choice of models and model relationships on the back-end. |
| 1 | Some separation of concerns on the front-end. Reasonable choices of models and relationships. |
| 2 | Clear separation of concerns on the front-end. Models and model relationships are well-chosen for the problem at hand. Controllers are 'skinny'. |
##### __Code Clarity__
Did you follow code style guidance and best practices covered in class, such as spacing and semantic naming? Did you comment your code as your instructors as we have in class?

| Score | Description |
|:-----:|:------------|
| 0 | Lots of missing semicolons in the JavaScript. Poor variable naming. Improper indenting _anywhere_. Excessive comments in the finished app. |
| 1 | Code is semantically correct. Naming isn't great, but is reasonable. Small number of select comments. |
| 2 | Code is extremely readable. Comments may be present, but are almost unnecessary because of how clear the code is. |
##### __Creativity__ :
Did you add a personal spin or creative element into your project submission? Is the finished product something of value to the end user, in addition to being functional (not just a login button and an index page)?

| Score | Description |
|:-----:|:------------|
| 0 | App is extremely simple, not extending at all beyond examples shown in class. |
| 1 | App shows some originality and inventiveness. |
| 2 | App is very novel - this might be because of the problem it solves, the way it solves a problem, or some creative element in the UI of the app. |

---

## GETTING STARTED

Not sure where to get started? Here's a sample timeline that you can follow for this project, if you so choose.

##### Week 5
* __Day 3__ : After receiving the project prompt, decide what kind of app to make, and begin sketching some rough wireframes for how the front end will look and act. Think about what kind of data your front-end will need from your back-end, and how that data will be used. Create two repos that your project will use, and add READMEs to both.
* __Day 4__ : Create a new vanilla Rails app for your back-end, but don't configure it. Create a simple front-end with HTML and CSS based (loosely) on your wireframes. Start reading up on any gems that you might want to include in your project.
* __Day 5__ : Begin writing JavaScript for DOM manipulation and AJAX on the front-end, mocking up your back-end as necessary.

##### Week 6
* __Day 1__ : Begin brainstorming about the kinds of data your application will use.
* __Day 2__ : Draw out your object relation model, and begin building the models and migrations to represent this data. Test your models using the Rails console.
* __Day 3__ : Add CORS to your API and begin making routes, testing them as you go using Postman. When they seem to work, try hitting the API from your front-end.
* __Day 4__ : Add authentication, if you haven't already.
* __Day 5__ : Do end-to-end testing of your app. Does it behave the way you'd expect?

##### Week 7
* __Day 1__ : Deploy your front-end and back-end apps.
* __Day 2__ : If everything's working, begin working on stretch goals.
* __Day 3__ : Continue working on stretch goals.
* __Day 4__ : Test and debug.
* __Day 5__ : Present!

> #### Some other thoughts to meditate on:
  * Begin with the end in mind. Know where you want to go by planning with wireframes & user stories, so you don't waste time designing and building things you don't need.
  * Remember that your backend environment is different from your browser environment – use tools to help you visualize it.
  * Don’t hesitate to write throwaway code to solve short term problems.
  * Read the docs for whatever technologies / frameworks / API’s that you use. Most of the time, there is a tutorial that you can follow, but not always, and learning to read documentation is crucial to your success as a developer
  * **Commit early, commit often.** As long as you do that, you don’t be afraid about breaking something, because you can always go back in time to a previous version.
  * User stories define what a _user_ wants to accomplish with your application. It's tempting to just make them todo lists for what needs to get done, but if you keep them small & focused on the user's needs, it'll help you know what ot build
  * Write pseudocode before you write actual code. Thinking through the logic of something helps.

Finally, here are some resources that it might be good for you to look at/read about:
* [Heroku Documentation](https://devcenter.heroku.com/) _(for hosting your back-end)_
* [Writing Good User Stories](http://www.mariaemerson.com/user-stories/) _(for a few user story tips)_
* [Presenting Information Architecture](http://webstyleguide.com/wsg3/3-information-architecture/4-presenting-information.html) _(for more insight into wireframing)_

#Good luck!
