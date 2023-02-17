# Scope Review Rubric Drew

> Note: There are exceptions to almost every rule here. If you have a good reason, it's possible that one of these checkboxes may not apply to you, but they apply to most, so they are good guideposts.

- [X ] Project Title
    - [X ] Has a title
    - [X] It's name doesn't change throughout the scope
- [ ] Application Overview
    - [X ] 2-5 Sentences explaining the application in non-technical terms
    - [X ] Someone who has never heard of the application can start to picture what it does.
    - [ X] Not just a description of the problem is that it is solving (generally speaking, clients will know what the problem is)
- [ ] Application Views
    - [X] Each view has a title
    - [ ] Each view has bullets describing what it does
    - [X ] Each view has a wireframe
        - [X ] Wireframes should typically not include color
    - [X ] If there are buttons, it should be clear what each button does. This can be listed on the wireframe or as a bullet
        - [ ] If a button takes a user to a different view, a bullet should call out the view name that it navigates to 
    - [X ] If the view is only accessible to some users, it should be clearly described in a bullet
    - [X ] Each view has a description of how users arrive there.
    - [X ] Ideally, stretch goals that the user feels are likely should be included in the views and noted as stretch goals in a bullet 
- [ ] Project Schedule
    - [X ] At a minimum, each view should have a date associated with it
    - [X ] The schedule is broken into features -- that is, a feature is a chunk of functionality that delivers demonstratable value
    - [X ] Each feature should have an appropriate due date (if all dates are the same, that is not valid)
    - [X ] There should be at least one feature per day, if a feature will take longer than a day, it is too large and should be broken down
    - [X ] The schedule should support a working, demonstrable CRUD app complete on the Thursday of the first week of work
    - [ ] All Base Mode features should be complete on the following Thursday (the week before final presentations)
- [ ] Browsers
    - [X ] Only include browsers you will actually be testing
    - [ ] Round up to the nearest whole number (ex Chrome 66, not Chrome 66.2384.239)
    - [ X] If you are including mobile browsers, include the phone you are supporting as well
- [X ] Assumptions
    - Assumptions can be anything you are basing your project upon. Often they are things outside of your control like assets you need from the client or a new technology you need to research. The idea is that if your assumptions are known to others, and they turn out to be incorrect, it may change how much effort your project will take.
    - They often raise questions that cannot be answered up front.
        - [ ] Client will provide all staff images
        - [ ] LibraryX can calculate parsnip trajectory. Documentation suggests it is possible but is not explicit.
        - [ ] App Administrators will give new users their password verbally
        - [ ] Any APIs you are using will not change
        - [ ] Any APIs you are using will not change their pricing
        - [ ] The API can do such and such (if the docs are unclear). If you need something from the API but don't know for sure it has it, you are making the assumption you can get it
- [ ] Entity Relationship Diagrams
    - [X ] Each table holds information about a _single Entity_
    - [X ] Each table has attributes, describing properties of the Entity
    - [X ] Everything shown in the wireframes is represented somewhere in the ERD
    - [X ] All data in the ERD is represented in the wireframes
    - [X ] Joins are used to describe one-to-many and many-to-many relationships
    - [X ] Joined tables have `REFERENCE`'ing ids in the correct table
- [X ] Review everything on every view. If it is not hard-coded it must be saved in the database.
- [ ] Technologies
    - [ ] All node modules installed with `npm install`
    - [ ] Database
    - [ ] File storage (Filestack, AWS, etc)
    - [ ] CSS library/framework
    - [ ] Deployment technologies (Heroku)
- [ ] Stretch/Future Goals
    - [X ] Should include feature title and brief description
    - [ ] Should take several months of full time effort to complete

## Final Pass

- [ ] All instructions in the scope are removed. It should no longer say things like: _This section should be short. Most of the details should be included in the views section._
- [ ] Is this actually reasonable?
    - [ ] Will CRUD be complete within a week?
    - [ ] Can base mode be completed on time for presentations?
