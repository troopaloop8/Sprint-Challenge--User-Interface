# Sprint Challenge: User Interface and Git - Multi-Page Website

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied Semantic HTML, CSS Fundamentals, CSS Flexbox Module, and Git. In your challenge this week, you will demonstrate proficiency by creating a multi page website that has some missing HTML elements as well as CSS specificity problems that need to be solved.  You will also create an additional web page that will be linked to from a navigation you will build.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, CSS flexbox module, and git.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons and your project manager.

## Description

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and create an additional page (About) which will link from the navigation you created.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home and about pages:

[Click here for the home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)

[Click here for the about page example](https://tk-assets.lambdaschool.com/ede1bb1a-63ff-4801-8c02-3efa2f603190_sprint-challenge-ui-about-example.png)

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. If you were to describe semantic HTML to the next cohort of students, what would you say?


Semantic HTML is the convention and practice of using tags that carry intended meaning and structure to an HTML document. For example, the use of an <h1> conveys importance, such as brand name. A <p> tag would contain written information, <nav> tags would be for navigation items, et cetera. This allows the structure of the HTML to be far more readable by humans and computers, and such code is better suited for team or open source projects.

2. Name two big differences between ```display: block;``` and ```display: inline;```.


display: block is an entire block of content. It can be of any specified width, and can include margin, borders, padding, and content. If the content spans many lines, the content box will expand, but the rest of the box model parameters would remain the same. Unlike how display: block applies the properties to an entire box, display: inline applies only to a line. This line takes up all the remaining space in its parent box unless specified in css. This can be used to create specific stylings.

3. What are the 4 areas of the box model?


On the outside, the margin can be considered the space around the box. Next is the border, which can be of any thickness, any color, and can select from various patterns. In between the border and the content is the padding. If content is in a border box, the padding would be the white space between the border and the content box, which is the box that hosts the content (text, image, video, etc)

4. While using flexbox, what axis does the following property work on: ```align-items: center```?

The align-items: center property centers the content along the cross-axis. This means that if you have a flex-direction: row, align-items will allow you to move the row up and down the y axis, so it could be at the top, center, or bottom of the box. If you have a flex-direction: column, then align-items: center will move across the x axis. You will be able to align the column so it starts at the left, center, or right side of its content box. 

5. Explain why git is valuable to a team of developers.

Git is a valuable tool and practice because it allows teams to collaborate efficiently. Whether you are working on a dedicated team, a personal project, or a open source project, it helps you to have version control. By having a history of each version and every change and who made the changes, you can iterate and grow the repository in a way that does not threaten the integrity of the project. If any one update breaks things, you can immediately revert the version and then that coder or someone else can inspect what went wrong and can fix it for the next update. Especially with many contributors to a project, version control allows others to work on the code to their own desire, and good contributions from the community can make their way into the main branch.

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Project Set Up

- [ ] Create a forked copy of this project.
- [ ] Add your project manager as collaborator on Github.
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.
- [ ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.
 
Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your project manager as a reviewer on the pull-request
- [ ] Your project manager will count the project as complete by merging the branch back into master.
 


## Minimum Viable Product

Your finished project must include all of the following requirements:

### Home Page

[Review the provided design file for the home page](design-files/home.png).  Notice the navigation and header images are missing.

* [ ] Build the HTML and CSS to create the missing navigation and header.
* [ ] Link the `About` navigation item to the [about.html](about.html) page

You will also notice there are 10 boxes on the home page that need background colors.  Use this list below to correctly style each box:

* [ ] box1: `teal`
* [ ] box2: `gold`
* [ ] box3: `cadetblue`
* [ ] box4: `coral`
* [ ] box5: `crimson`
* [ ] box6: `forestgreen`
* [ ] box7: `darkorchid`
* [ ] box8: `hotpink`
* [ ] box9: `indigo`
* [ ] box10: `dodgerblue`

### About Page

[Review the provided design file for the about page](design-files/about.png). You have been provided the HTML wrapper, footer, and page content for the about page. Create the rest of the missing HTML and CSS to match the design file.

* [ ] Copy and paste your home page navigation and header into the about page
* [ ] Update the header image with the about page image
* [ ] Link the `Home` navigation item back to the `index.html` page.
* [ ] Build the rest of the about page layout to match the design

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Build a page of your choosing from the navigation items.  Come up with content and images that fit the theme.  
* [ ] Introduce CSS animations to your site.
* [ ] Build a contact page and create a form with several inputs of your choosing
* [ ] Add responsive breakpoints to your code by using media queries
