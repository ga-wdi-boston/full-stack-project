[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Building A  Full-Stack Application

This second project will be your first foray into building a full-stack
application. You'll be building your first real back-end app, with a
front-end to match, which means you'll learn about what it takes to build an
API and use it.

At a high level, here are our goals for you in this project:

-   Build a single-page application (SPA) with basic user authentication that
    interacts with a custom API that you build
-   Build an app that can create, read, update, and delete data in a SQL
    database
-   Learn to create user stories and wireframes (before writing code) as part of
    planning out your app.
-   Learn to confidently present your work to a technical audience (5-10 minute
    presentation)

You will be working individually for this project, and you'll be designing the
app yourself. Remember to keep things small – scope creep/feature creep is a
huge potential pitfall for any project!

## Deliverables

-   A **working full-stack application, built by you**, hosted somewhere on the
    internet.
-   **Two Github repos** (one for your front-end and one for your back-end),
    with frequent commits dating back to the very beginning of the project. Each
    repo will need a **README.md file** with a link to the other repo. Your
    front-end repo's README should also have

    -   An **explanation** of the what the app does and how it works, the
        approach taken in building it, and any unsolved problems that you hit.
    -   **User stories** written for your app.
    -   At least one **wireframe** (or a link to one) that you've created to
        plan out your app.
    -   A **link** to the live application.

In order to get a satisfactory score, your app must:

-   Have an **API** that is securely accessible by your browser app, built using
    frameworks covered in class.
-   Create **at least 4 RESTful routes** for handling GET, POST, PUT/PATCH, and
    DELETE requests. Any actions which change data must be authenticated, and
    the data must be "owned" by the user performing the change.
-   **Utilize an ORM** to create a database table structure and interact with
    data
-   **Use a front-end Javascript app** to communicate with your API (both read
    and write) and render data that it receives in the browser.
-   Have **semantically clean HTML and CSS**
-   Be **deployed online**, so that it is accessible to the public

### Bonus

Once (and only once) you've satisfied the core requirements, here are some
additional goals that you can shoot for:

-   Incorporate Bootstrap, Handlebars, or some other front-end tool.
-   Interact with third-party APIs and integrate them into your app.
-   Put some extra thought and effort into visual and UI design.

## Feedback

These are the things that consultants will be looking at, and giving you
feedback on, after you've submitted your project.

### Project Workflow

-   **Planning** : Did you complete user stories and wireframes before you
    started writing code? Did you create a schedule for yourself to keep your
    project on track?
-   **Source Control** : Did you use source control to keep track of changes in
    your project and make regular 'save points' for yourself?

### Deliverables

-   **Technical Requirements** : Does your project meet all the technical
    requirements outlined above? Does it run?
-   **Software Design/Problem Solving** : How did you break up the functionality
    of your application? How did you solve the problems that you encountered
    along the way? Do the solutions you came up with make sense, from the
    perspective of industry best practices? How well can you defend the choices
    you've made?
-   **Code Clarity** : Did you follow code style guidance and best practices
    covered in class, such as spacing and semantic naming? Did you comment your
    code as your s as we have in class?
-   **Creativity** : Did you added a personal spin or creative element into your
    project submission? Is the finished product something of value to the end
    user, in addition to being functional (not just a login button and an index
    page)?

## Overall Score

Your consultants will give you a total score on your project as an aggregate
across all feedback categories:

| Score | Expectations                                           |
|-------|--------------------------------------------------------|
| **0** | _Does not meet expectations._                          |
| **1** | _Meets expectactions, good job!_                       |
| **2** | _Exceeds expectations, you magnificent creature, you!_ |

This will serve as a helpful overall gauge of whether you met the project goals.
But more important than your overall score is your feedback, particularly in
individual categories - this will help you identify where to focus your efforts
for future projects.

## Getting Started

Most importantly, remember to **go slowly and be methodical**. That means you
should be testing your changes in-browser as you write each line or so of code.
Always be committing. Deploy early and often.

Here's a rough sketch of what you should do and in what order:

-   [ ] After receiving the project prompt, decide what kind of app to make, and
    begin sketching some rough wireframes for how the front end will look and
    act.
-   [ ] Think about what kind of data your front-end will need from your
    back-end, and how that data will be used. Create an ERD.
-   [ ] Create two repos that your project will use, and add READMEs to both.
-   [ ] Create a simple front-end with HTML and CSS based (loosely) on your
    wireframes.
-   [ ] User our
    [`rails-api-template`](https://github.com/ga-wdi-boston/rails-api-template)
    for your back-end. It already includes authentication.
-   [ ] After you have an ERD, check with a consultant to ensure your data model
    is appropriate for your goals. Then, build the models and migrations to
    represent this data. Test your models using the Rails console, and test your
    API endpoints using `curl`. You may also write automated tests in RSpec if
    you choose.
-   [ ] Before working on the front-end application, ensure all back-end
    endpoints work as expected. Knowing the back-end well will help you diagnose
    bugs on the front-end.
-   [ ] Write your front-end application using JavaScript, jQuery, and AJAX.
-   [ ] Test, commit, and deploy often! Test, commit, deploy! Test your
    deployments!
-   [ ] When main features are finished, begin working on stretch goals and
    icebox features.
-   [ ] Finish your documentation. Make it high-quality.

## Tips

-   Begin with the end in mind. Know where you want to go by planning with
    wireframes and user stories, so you don't waste time designing and building
    things you don't need.
-   Remember that your backend environment is different from your browser
    environment – use tools to help you visualize it.
-   Don’t hesitate to write throwaway code to solve short term problems.
-   Read the docs for whatever technologies / frameworks / API’s that you use.
    Most of the time, there is a tutorial that you can follow, but not always,
    and learning to read documentation is crucial to your success as a
    developer.
-   **Commit early, commit often.** As long as you do that, you don’t be afraid
    about breaking something, because you can always go back in time to a
    previous version. Always work on a branch!
-   User stories define what a _user_ wants to accomplish with your application.
    It's tempting to just make them todo lists for what needs to get done, but
    if you keep them small and focused on the user's needs, it'll help you know
    what to build.
-   Write pseudocode before you write actual code. Thinking through the logic of
    something helps.

Finally, here are some resources that it might be good for you to look at/read
about:

-   [Heroku Documentation](https://devcenter.heroku.com/)
-   [Writing Good User Stories](http://www.mariaemerson.com/user-stories/)
-   [Presenting Information Architecture](http://webstyleguide.com/wsg3/3-information-architecture/4-presenting-information.html)

**Good luck and happy hacking!**

## [License](LICENSE)

Source code distributed under the MIT license. Text and other assets copyright
General Assembly, Inc., all rights reserved.
