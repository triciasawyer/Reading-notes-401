# Reading notes class 2

## An introduction to NodeJS and Express

**Explain middleware, answer as though I were a non-technical recruiter.**
It is software that lies between an operating system and the applications running on it. Middleware are packages that are created to address almost any web development problem. There are libraries to work with cookies, sessions, user logins, URL parameters, POST data, security headers, and many more.

**Express the most popular __ __ ____.**
Node web framework

**Express is “unopinionated.” What does that mean?**
This phrase means that when using express, you can insert almost any compatible middleware you like into the request handling chain, in almost any order you like. You can structure the app in one file or multiple files, and using any directory structure. So, in other words, it isn't picky.

**What is a module and why is modularity useful to us as developers?**
A module is a JavaScript library/file that you can import into other code using Node's 'require()' function. Express itself is a module, as well as the middleware and database libraries that we use in our Express applications. It is useful because it allows developers to be organized and write clean code.

## What is NPM?

**What version of npm are you running on your machine?**
npm 9.5.0

**What command would you type to install a library/package called ‘jshint’ into your node project?**
npm install jshint

## What is TDD?

**Explain why tests are important. Please explain as though I were your non technical elder.**
A big benefit that comes from testing code is identification and removal of errors. Testing also helps developers and testers compare actual and expected results in order to improve quality.

**What are three expected benefits of testing?**

+ Many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort.

+ The same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases.

+ Although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling.

**Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.**
Individual pitfalls

+ forgetting to run tests frequently
+ writing too many tests at once

Team pitfalls

+ partial adoption – only a few developers on the team use TDD(test-driven-development)
+ poor maintenance of the test suite – most commonly leading to a test suite with a prohibitively long running time

## CI/CD

**What are three benefits of Continuous Integration?**g

+ Fault Isolations
+ Faster Mean Time To Resolution (MTTR) ...
+ More Test Reliability. ...

**What is the difference between Continuos Delivery and Continuous Deployment?**
Continuous Delivery is a software engineering practice where the code changes are prepared to be released. Continuous Deployment aims at continuously releasing the code changes into the production environment.

**Explain how GitHub fits into this process assuming the listener comes from a non-technical background.**
GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere, and GitHub fits into this process because as we use github to host our written code, we need tests to be written to test our code and then those tests need to be passing to then be able to host it correctly on our hosting platform, GitHub.

## What are your learning goals after reading and reviewing the class README?

My goals are to learn how to write and run a test properly. Also excited to learn about super test and the backend overall.
