# OSMICS
[![ci-osmics](https://github.com/ics414t3/ics-osm/actions/workflows/ci.yml/badge.svg)](https://github.com/ics414t3/ics-osm/actions/workflows/ci.yml/)


## Table of Contents
* [Overview](#overview)
* [Goals](#goals)
* [What Our Application Provides](#what-our-application-provides)
* [Mockup Pages](#mockup-pages)
* [User Guide](#user-guide)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Deployment](#deployment)
* [Quality Assurance](#quality-assurance)
* [Team Members](#team-members)

## Overview
The ICS department is in need of an office space management system. Currently, there is no management system, which makes it difficult to reassign offices or assess rooms' inventory.

## Goals
Our goal is to develop a user friendly application that can assist the entire ICS department with distribution of key information and management.

## What Our Application Provides
This application will mainly provide the ICS Department's administrative office and tech support with an inventory and office space management system. Additionally, students and faculty also have access to the site, but with a different scope. Faculty can book conference rooms, and can update their office hours. Students on the other hand can look up faculty members, or locate where a certain room may be. 

## Mockup Pages

### Landing Page
What the user sees when they first go to the site.
![landing](/assets/images/m2/landing.png)

### Sign-In
Where the user can sign-in.
![sign-in.png](/assets/images/m1/login-page.png)

### Profile Page
This is where users are able to view their profile / account information.
![profile](/assets/images/m1/profile-page.JPG)

### Admin Page
Admin can see all of the users and modify their information.
![admin](/assets/images/m2/admin.png)

### Admin List Room
Admin can see all of the rooms and modify their information.
![admin](/assets/images/m2/room-admin.png)

### Reserve
Where admin, faculty, tech, or office can reserve rooms.
![calendar](/assets/images/m2/calendar.png)

### Faculty Page
Where the list of faculty can be seen by all users. However, only admin and office can add new faculty.
![faculty](/assets/images/m2/faculty.png)

### Add Faculty
Modal that allows admin or office to add faculty.
![add-faculty](/assets/images/m2/add-faculty.png)

### Room Page
![list-room](/assets/images/m2/list-room.png)

## User Guide
In progress

## Developer Guide
First, install [Meteor](https://www.meteor.com/install).

Next, go to the [OSMICS hithub page](https://github.com/ics414t3/ics-osm). and make a copy of the repo to your local computer.

Then, cd into the app directory and use:

```
meteor npm install
```

And finally, run the system with:

```
meteor npm run start
```

If everything is good, the application will appear at [http://localhost:3000](http://localhost:3000).

## Development History
The development process for OSMICS follows Issue Driven Project Manaagement:

* Development consists of a sequence of milestones.
* Each milestone is specified as a set of tasks.
* Each task is described using a Github Issue, and is assigned to a single developer.
* The work for each task is accomploished with a gut branch named "issue-XX", where XX is replaced by the issue number.
* When a task is complete, its corresponding issue is closed and its git branch is merged into main.
* The state of each task for a milestone is managed using a Github Project Board.


- **[M1](https://github.com/orgs/ics414t3/projects/1/views/1)** (Milestone 1)
  - Completed Mockups
- **[M2](https://github.com/orgs/ics414t3/projects/2)** (Milestone 2)
  - Implemented pages based on the mockups
- **[M3](https://github.com/orgs/ics414t3/projects/3)** (Milestone 3)
 

## Deployment
In progress

## Quality Assurance
In progress

## Team Members
- Devin Arquines
- James Louie Grande
- Malia Liu
- Susan Ma
- Gwyneth Raquepo
- Giorgio Tran
- Jerome Wasserman

[Team Contract](./team-contract.pdf)

For comments or questions, please contact us via our project's [GitHub](https://github.com/ics414t3).
