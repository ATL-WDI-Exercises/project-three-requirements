# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project #3: Building Your Own API

### Overview

You’ve already worked in small groups to accomplish various labs and exercises, but this time **we’re going to challenge you to work on a whole project with a small team.**

Not only will you be asked to **exercise additional creativity** in designing your own project, your instructors will partner you with other classmates to architect, design, and collaboratively build a full-stack web application of your own design.

While your last project taught you how to get started with Ruby, SQL, & Ruby on Rails, this project you'll be building something exciting with **Express & Mongo.**

**This is meant to push you both technically and collaboratively.** It’s a lot harder to work in a team than to work by yourself, but that's most likely you’re going to find yourself doing in your first development job after WDI, and **it's important to learn how to work together.**

Make it work, and make it awesome.

---

### Technical Requirements

Your app must:

* **Use Mongo & Express** to build an full-stack web application using server-side Javascript
* **Use at least 2 related models**, one of which should be a user
* Follow the **RESTful** best practices - all routes should be defined using an HTTP GET/PUT/POST/DELETE on a URL that represents the resource being accessed
* Include **all major CRUD functions** for at least one of the models
* **Add authentication and authorization** to your web application to restrict access to appropriate users
* **Craft thoughtful user stories together**, as a team
* **Manage team contributions and collaboration** using a standard Git flow on Github
* Layout and style your front-end with **clean & well-formatted CSS**
* **Deploy your application online** so it's publically accessible

Bonuses:

* Add some **client-side rendering** with Javascript & jQuery (i.e. making AJAX calls to the server)
* Consume a 3rd party API

---

### Necessary Deliverables

* A **working web application, built by the whole team**, hosted somewhere on the internet
* A **link to your hosted working app** in the URL section of your Github repo
* A **team git repository hosted on Github**, with a link to your hosted project, and frequent commits from _every_ team member dating back to the _very beginning_ of the project
* **A ``readme.md`` file** with:
    * Explanations of the **technologies** used
    * A couple paragraphs about the **general approach you took**
    * **Installation instructions** for any dependencies
    * Link to your **user stories** – who are your users, what do they want, and why?
    * Link to your **wireframes** – sketches of major views / interfaces in your application
    * Descriptions of any **unsolved problems** or **major hurdles** your team had to overcome
    * **Future vision** for the project

---

### Suggested Ways to Get Started

* **Don’t hesitate to write throwaway code** to solve short term problems.
* **Read the docs for whatever technologies / frameworks / API’s you use**.
* **Write your code DRY** and **build your routes using RESTful best practices**.
* **Be consistent with your code style.** You're working in teams, but you're only making one app per team. Make sure it looks like a unified effort.
* **Commit early, commit often.**
* **Keep user stories small and well-defined**, and remember – user stories focus on what a user needs, not what development tasks need accomplishing.
* **Write code another developer wouldn't have to ask you about**. Do your naming conventions make sense? Would another developer be able to look at your app and understand what everything is?
* **Make it all well-formatted.** Are you indenting, consistently? Can we find the start and end of every div, curly brace, etc?
* **Comment your code.** Will someone understand what is going on in each block or function? Even if it's obvious, explaining the what & why means someone else can pick it up and get it.
* **Write pseudocode before you write actual code.** Thinking through the logic of something helps.

---

### GIT and GitHub Best Practices for Team Projects

Here are some best practices for using Git and GitHub in a one-week team project.

* **Use One GitHub Repo:**  Choose one person to create the GitHub repo. All teammates will clone from one GitHub repo. At the end of the project, teammates may fork the repo if they want to have ownership over their own fork.
* **Use Feature Branches:**  Each developer should do their work in a feature branch and coordinate with the team when to merge back into the master branch. Try to merge no less than once per day.
* **Pull Before Merging:**  Always do a pull before a merge to make sure that you are merging into the latest version of the branch.
* **Rebase Feature Branches:**  Rebasing is a good way to keep a feature branch up to date with the master. Thus you will rebase to update your feature branches and merge to update the master branch. The flow would look like this:
  - complete work on feature branch, test and commit to feature branch
  - checkout master and pull to get latest changes to master
  - if any changes were pulled into master, then
    - checkout feature branch and rebase (or merge) to include latest changes from master into feature branch
    - test feature branch again (this time with latest changes from master)
    - checkout master
  - now merge feature branch into master
  - push master to GitHub with changes from the feature branch
* **Deploy From Master Branch:**  The master branch should be used for deployments to Heroku.

---

### Potential Project Ideas

For this project, we want you to work with your team to build a creative product that you actually think someone will want to use. We won't have time to do tons of customer research, but take some time to brainstorm. If you're struggling for ideas, the ones below could help get you started.

##### Bucketli.st
Besides finishing WDI, you surely have one or two things you'd love to do with your life. Let's get 'em on paper! You could integrate with a third-party location-based API to allow users to search for a location or venue to add to their bucket list items.

##### Survey App
Imagine sending out a survey to everyone in the class – what should we eat for lunch today? Or 1-5, how well did you understand what we just learned? It would be even more awesome if it were realtime, so you could see answers pouring in as they're submitted.

##### Hello, Comments
Imagine the benefits of having an API where you could embed comments into any website you want. They could even update in realtime if you wanted, so that you'd never have to refresh the page. CMS providers across the world could quit writing code from scratch and just embed your widget instead.

---

### Useful Resources

* **[MongoDB](https://www.mongodb.org/)**
* **[Express JS](http://expressjs.com/)**
* **[Getting Started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)**

---

### Project Feedback + Evaluation

* __Project Workflow__: Did you complete the user stories, wireframes, task tracking, and/or ERDs, as specified above? Did you use source control as expected for the phase of the program you’re in (detailed above)?

* __Technical Requirements__: Did you deliver a project that met all the technical requirements? Given what the class has covered so far, did you build something that was reasonably complex?

* __Creativity__: Did you added a personal spin or creative element into your project submission? Did you deliver something of value to the end user (not just a login button and an index page)?

* __Code Quality__: Did you follow code style guidance and best practices covered in class, such as spacing, modularity, and semantic naming? Did you comment your code as your instructors as we have in class?

* __Problem Solving__: Are you able to defend why you implemented your solution in a certain way? Can you demonstrated that you thought through alternative implementations? _(Note that this part of your feedback evaluation will take place during your one-on-one code review with your instructors, after you've completed the project.)_

* __Total__: Your instructors will give you a total score on your project between:

    Score | Expectations
    ----- | ------------
    **0** | _Incomplete._
    **1** | _Does not meet expectations._
    **2** | _Meets expectactions, good job!_
    **3** | _Exceeds expectations, you wonderful creature, you!_

 This will serve as a helpful overall gauge of whether you met the project goals, but __the more important scores are the individual ones__ above, which can help you identify where to focus your efforts for the next project!
