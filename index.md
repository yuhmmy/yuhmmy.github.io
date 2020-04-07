## yUHmmy
## Table of contents

* [Overview](#overview)
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Walkthrough Videos](#walkthrough-videos)
* [Example enhancements](#example-enhancements)
* [Contact US](#contact-us)
* [Acknowledgements](#acknowledgements)

## Overview
It is a known fact that good restaurants and bars usually have long wait times in respect to service response time, and it is also a terrible idea to keep hungry people waiting. Our mobile point of sales platform eliminates the waiting game for customers by automating the process and putting it online, so if you have a mobile device you never have to track down a waitress ever again, or awkwardly try to get the bartenders attention at Manoa Gardens. Furthermore as long as the customer has a debit card on their account they can pay for their services and tip and waitress without even reaching for their wallet. This makes the ordering process less daunting and more convenient for both patrons and the business establishment.

It illustrates various technologies useful to ICS software engineering students, including:

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

### Approach
This project is similar to grubhub such that users can order and pay for food on their mobile device and similarity ends there, the following is a list of things that make our platform great:
* Order and have your food brought to your table eliminating multiple trips for wait staff
* The users can set limits on spending so they don’t overspend.
* Order drinks or request services in restaurants
The features above is intended to eliminate as much interaction between wait staff and customer. The goal is to make the customer feel like, their food appeared in front of them magically. This also allow the restaurant to spend more of their man power moving goods since that is what makes the money.

## User Guide
This section provides a walkthrough of the yUHmmy user interface and its capabilities.

### Landing Page
The landing page is presented to users when they visit the top-level URL to the site.

### Settings page
### Menu page
### Profile page
### Billing page
### Restaurant critique page

## Community Feedback
We are interested in your experience using yUHmmy!

## Developer Guide
This section provides information of interest to Meteor developers wishing to use this code base as a basis for their own development tasks.

### Installation
First, [install Meteor](https://www.meteor.com/install).

Second, visit the [yUHmmy application github page](https://github.com/yuhmmy/yuhmmy), and click the "Use this template" button to create your own repository initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the repo.  However you do it, download a copy of the repo to your local computer.

Third, cd into the yuhmmy/app directory and install libraries with:

```
$ meteor npm install
```

Fourth, run the system with:

```
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).


### Application Design
yUHmmy is based upon [meteor-application-template-react](https://ics-software-engineering.github.io/meteor-application-template-react/) and [meteor-example-form-react](https://ics-software-engineering.github.io/meteor-example-form-react/). Please use the videos and documentation at those sites to better acquaint yourself with the basic application design and form processing in yUHmmy.

### Data model
## Initialization
The [config](https://github.com/bowfolios/yuhmmy/tree/master/config) directory is intended to hold settings files. The repository contains one file: config/settings.development.json.

This file contains default definitions for Profiles, Projects, and Interests and the relationships between them. Consult the walkthrough video for more details.

## Quality Assurance

### ESLint
yUHmmy includes a [.eslintrc](https://github.com/yuhmmy/yuhmmy/blob/master/app/.eslintrc) file to define the coding style adhered to in this application. You can invoke ESLint from the command line as follows:

```
meteor npm run lint
```

ESLint should run without generating any errors.

It's significantly easier to do development with ESLint integrated directly into your IDE (such as IntelliJ).

### From mockup to production


## Development History

The development process for BowFolios conformed to [Issue Driven Project Management](http://courses.ics.hawaii.edu/ics314f19/modules/project-management/) practices. In a nutshell:

* Development consists of a sequence of Milestones.
* Each Milestone is specified as a set of tasks.
* Each task is described using a GitHub Issue, and is assigned to a single developer to complete.
* Tasks should typically consist of work that can be completed in 2-4 days.
* The work for each task is accomplished with a git branch named "issue-XX", where XX is replaced by the issue number.
* When a task is complete, its corresponding issue is closed and its corresponding git branch is merged into master.
* The state (todo, in progress, complete) of each task for a milestone is managed using a GitHub Project Board.

The following sections document the development history of yUHmmy.

### Milestone 1: Mockup development
The goal of Milestone 1 was to create a set of HTML pages providing a mockup of the pages in the system.

### Milestone 2: Data model development
The goal of Milestone 2 was to implement the data model: the underlying set of Mongo Collections and the operations upon them that would support the yUHmmy application.

### Milestone 3: Final Touches
The goal of Milestone 3 was to clean up the code base and fix minor UI issues.

## Walkthrough Videos
yUHmmy is intended as a model of how an ICS 314 project could be organized and executed. Here are several videos that walks you through various aspects of the system:

## Example Enhancements

After implementing the basic functionality, here are ideas for more advanced features:

* Restaurant Suggestions based on previous orders using machine learning
* Able to provide party hot spots based on number of people at restaurants or bars
* Ratings and reviews for restaurants
* Give alerts for new menu items
* Suggest restaurants based on budgets

## Contact Us
Meet the Team!
* [Keenan Lee](https://knolee.github.io/)
* [ZJ Lin](https://z-j-lin.github.io/)
* [Tina Loos](https://tinaloos.github.io/)
* [Spencer Young](https://spjy.github.io/)

## Acknowledgements

Mahalo nui loa to [Phillip Johnson](https://github.com/philipmjohnson) for the knowledge on software engineering and guidance that was provided thoughout the semester, as well as documentation formatting.
