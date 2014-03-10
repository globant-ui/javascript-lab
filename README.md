JavaScript Lab
==============

##Target Audience
This lab targets Web UI developers regardless of their current seniority. However, is expected a basic knowledge on web technologies such as HTML, CSS, and JavaScript. This lab is not a tutorial on web technologies, its objective is to teach through the resolution of challenging problems.

Through the completion of this lab you will learn the following skills:
- Vanilla JavaScript
- JavaScript Best Practices
- Raw interaction with the browser APIs. No libraries will be allowed, except for BDD.

##Introduction
The lab will be considered completed by the developer once he has finished all the exercises and uploaded them to GitHub. In addition, the exercises must be deployed in GitHub pages so it can be used online. The evaluation will be done through code reviews using GitHub’s review tools.

Please fork this repository, and send a PR as soon as the lab is finished. Afterwards, the PR will be evaluated by an architect or senior developer.

##Reading material
ToDO

##Exercises
1. Complete the following JavaScript assessment: https://github.com/rmurphey/js-assessment

2. Implement a Pub/Sub library: http://en.wikipedia.org/wiki/Publish%E2%80%93subscribe_pattern. Provide unit tests, Jasmine can be used.

3. Implement a Promise library based on the following specification: http://promises-aplus.github.io/promises-spec/. Provide unit tests, [Jasmine](http://jasmine.github.io/2.0/introduction.html) can be used.

4. Implement a library to perform AJAX calls. Define your API without callbacks, reuse your promise library. The library must work across different browsers IE9+, Chrome, FF, Safari. Provide unit tests, [Jasmine](http://jasmine.github.io/2.0/introduction.html) can be used.

5. Create a Pacman game. Design your application using an object-oriented approach. Use the module pattern to structure your implementation. Implement Ghost's AI algorithm following [this](http://gameinternals.com/post/2072558330/understanding-pac-man-ghost-behavior) article. Add sounds to the different game actions.
  * This exercise will be evaluated on the basis of design, and code quality. The game must be structured following a saneobject-oriented structure. Implementation must reflect JavaScript best practices. This exercise will not be evaluated on the basis of cross-browsing, or performance issues.
  * Is encouraged the use of the canvas, and audio APIs. 
  * No library or framework can be used. You can reuse the libraries developed in the previous exercises.
  * Provide unit tests, [Jasmine](http://jasmine.github.io/2.0/introduction.html) can be used.

6. Single-Page Application Development. Create an application that allows a user to:
  1. Authenticate to GitHub.
  2. List all starred repositories she has.
  3. Present a detailed view of a repository.
  4. Allow her to unstar, watch, and unwatch a given repository.
  5. This exercise will be evaluated on the basis of design, and code quality. 
    - The game must be structured following a sane object-oriented structure. Implementation must reflect JavaScript best practices. The application must work across all major browsers (IE9+, Chrome, Firefox, Safari).
    - No library or framework can be used. You can reuse the libraries developed in the previous exercises.
    - Provide unit tests, [Jasmine](http://jasmine.github.io/2.0/introduction.html) can be used.
