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
![landing](/assets/images/m3/landing.png)

### Sign-In
Where the user can sign-in.
![sign-in.png](/assets/images/m3/sign-in.png)

### Home Page
A home page that includes a zoomable map of POST. Faculty is also visible as well as room reservations. The blue hovering button is for accessibility.
![home.png](assets%2Fimages%2Fm4%2Fhome.png)

### Admin Page
Admin can see all of the users and modify their information.
![admin](/assets/images/m3/admin.png)

### Room Admin
Admin can see all of the rooms and modify their information, can add rooms, and view room details.
![admin](/assets/images/m3/room-admin.png)
![add-room.png](assets%2Fimages%2Fm3%2Fadd-room.png)
![room-details.png](assets%2Fimages%2Fm3%2Froom-details.png)

### Faculty Page
Where the list of faculty can be seen by all users. However, only admin and office can add new faculty.
![faculty](/assets/images/m3/faculty.png)
![add-faculty.png](assets%2Fimages%2Fm3%2Fadd-faculty.png)
![faculty-profile.png](assets%2Fimages%2Fm3%2Ffaculty-profile.png)

### Discussion Page
Where users can make posts or announcements Reddit style.
![discuss.png](assets%2Fimages%2Fm3%2Fdiscuss.png)

### Clubs
Each club has their own page with various information such as meeting times, Discord invites, and more.
![clubs.png](assets%2Fimages%2Fm4%2Fclubs.png)
People with the role of Admin or Office also have the ability of adding clubs. 
![add-club.png](assets%2Fimages%2Fm4%2Fadd-club.png)

## User Guide
In progress

## Developer Guide
First, install [Meteor](https://www.meteor.com/install).

Next, go to the [OSMICS github page](https://github.com/ics414t3/ics-osm). and make a copy of the repo to your local computer.

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
The development process for OSMICS follows Issue Driven Project Management:

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
  - Revamp user interface
  - Add an interactive map prototype
  - Add more functionality such as adding rooms, adding faculty, and a discuss page
- **[M4](https://github.com/orgs/ics414t3/projects/6)** (Milestone 4)
  - Further improvements in the user interface
  - Add club collections
  - Add club pages and clubs in the navigation bar
  - Reimplemented logic for Roles
- **[M5](https://github.com/orgs/ics414t3/projects/8)** (Milestone 5 --- in progress.)
 

## Deployment
In progress

## Quality Assurance
To ensure quality assurance, we are using several tools including eslint and testcafe.

To run testcafe for development run:
```
$ meteor npm run test-acceptance-development
```
To run testcafe with headless (similar to how it will run once committed to Github) run:
```
$ meteor npm run test-acceptance-ci
```
To run eslint:
```
$ meteor npm run lint
```

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
