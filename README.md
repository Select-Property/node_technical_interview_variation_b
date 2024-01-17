# Vita Group - Node JS Coding Challenge

Thanks for taking the time to do our node engineering test.

You are free to use any resources or references you want, except for direct help from others.

You can use any development environment or tools that you feel comfortable with.

**Bonus Points**

* Using Typescript

* Using Docker

----

## Exercise 1:

Backend (Node.js - Any framework or tools necessary):

### Create a RESTful API with two endpoints:
GET /properties - to retrieve a list of property listings.
POST /properties - to add a new property listing.
Implement basic in-memory storage for property listings (no database required).

Frontend (Javascript - Any framework or tools necessary):

### Develop a simple UI with two components:
* A list view to display all properties fetched from the backend.
* A form to add a new property listing.
* Ensure the UI is user-friendly and responsive.

### Evaluation Criteria:
* Code Quality: Clean, readable, and well-structured code.
* Functionality: The application works as expected without bugs.
* Design: Basic but effective UI/UX design.
* Problem Solving: Efficient and effective solutions to the problems.

----

## Exercise 2: A Tale of Request Latency

We've created a new blog service but we can forsee some potential issues.

When we retrieve a blog posts we also need to make an extra request to retreive it's outreach information from a thrid party service. 

Currently this is not an issue with there being a low number of blog posts per aurthor, but in the future this may become a problem with the number of posts increasing. 

The latency per request to the thrid party is unknown. Can you provide any solutions for how we could tackle this problem?

----

## Submission Guidelines

* The zip file should be named {yourname}.zip, and should itself contain the node tech test project folder with your submission.

* The zip file should contain the [FOLLOW-UP.md](./FOLLOW-UP.md) file with answers to the follow-up questions.

* The zip file should **not** include the `node_modules` folder. (If Applicable)
