# Study Buddy

## Overview

UHM Study is a web application for students to find study buddies online. It allows users to connect and schedule study sessions. The goal of this project is to solve students' issues with not having someone to study with. This project aims to increase student productivity and network.

* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [React Bootstrap](https://react-bootstrap.github.io/) CSS Framework for UI design.

## User guide

### Home Page

The home page provides an overview of the application features, including multiple users, contact details, and timestamped notes.

<img src="doc/newfront.png" alt="Landing Page Screenshot">

### About Page

About Page provides a brief overview of Study Buddy and its uses

<img src="doc/aboutdamn.png" alt="Landing Page Screenshot">

### Tutorial

The Tutorial Page offers a video demo of how to use Study Buddy

<img src="doc/tutorial.png" alt="Landing Page Screenshot">

### Sign Up Page

The sign-up page allows users to create an account. Users need to provide their email and password to sign in.

<img src="doc/signup.png" alt="Landing Page Screenshot">

### Sign In Page

The sign-in page allows users to log in to their accounts. Users need to provide their email and password to sign in.

<img src="doc/signup.png" alt="Landing Page Screenshot">



### Create Profile Page

Create a profile by adding the fields of your profile page like name, bio, social, major, etc allowing people to connect with specific people who take the same classes

<img src="doc/createProfile.png" alt="Landing Page Screenshot">

### My Profile Page

This page features your account information. The profile includes name, major, bio, and socials. The session will include a title, class, creator, date and time, place, collaborators, and a description
The My Sesions Page will provide study session you have joined with all the information about the session

<img src="doc/myProfile.png" alt="Landing Page Screenshot">

### Edit Profile Page

Customize and edit the fields of your profile page like name, bio, social, major, etc allowing people to connect with specific people who take the same classes

<img src="doc/editProf.png" alt="Landing Page Screenshot">

### Sessions

Provides a list of available study sessions to join with description of when, where, who, and what allowing for easy efficent connections

<img src="doc/sessions.png" alt="Landing Page Screenshot">

### Create Sessions

The Create Session Page allows you to create a study session describing What you're studying, where you want to study, and when you want to study in hopes of connecting with others who are studying the same 

<img src="doc/CreateSes.png" alt="Landing Page Screenshot">

### Edit Session

The edit session page allows users to edit the study sessions that they created

<img src="doc/editSession.png" alt="Landing Page Screenshot">

### My Sessions

My Sessions page shows all sessions that you added and created

<img src="doc/mySessions.png" alt="Landing Page Screenshot">

### Edit Session

The edit session page allows users to edit the study sessions that they created

<img src="doc/editSession.png" alt="Landing Page Screenshot">


### Buddies

The Buddies Page shows a list of buddies you can find, add, and filter which buddies you added. Similar to a friends list on video games like Brawl Stars

<img src="doc/bud.png" alt="Landing Page Screenshot">


### Buddy Profile

The Buddy Profile Page shows the list of all contacts as Admin view.

<img src="doc/budprof.png" alt="Landing Page Screenshot">

## Developer Guide
1. First Clone our github project [repository](https://github.com/uhm-studymax/study-buddy)
2. Open terminal in VScode and type ``npm install``
3. Setup your database using NEON DB POSTGRESQL with VERCEL
    - [Summarized Database Setup Guide](https://docs.google.com/document/d/1aVrZkc9hd2ATA0mQhpRm5HO-mKOJemiUF-Agwj6JGHE/edit?usp=sharing)
    - [ICS 314 Deployment Module](https://courses.ics.hawaii.edu/ics314f24/modules/deployment/![image](https://github.com/user-attachments/assets/f139a0da-6bc0-4bde-8ce9-e0fb9dfa255c)
)
4. Configure your cloud database in AWS
   - Create an AWS account
   - Using S3 service, create a bucket
   - Setup and create IAM user
   - Create access keys then transfer those values to your into .env file
   - Configure IAM user policies to allow for S3 bucket permissions along with CORS setup
5. Run your project
   - Go into terminal on VScode, type: ``npm run dev``
   - The site should then be running on [https://localhost:3000](https://localhost:3000)

## Team
Team Members:

- Ralph Ramos
- Wilson Huynh
- Lukas Moroz
- Reo Nagahama

## Team Contract
- [Team Contract](https://docs.google.com/document/d/1CuqpTS5TcGMRY66bBHws0psp6xEzRiAeooaWMurNlUc/edit?tab=t.0)

## Organization Page:
 - [Organization Page](https://github.com/uhm-studymax)

## Milestone 1:
The goal of Milestone 1 was to create a set of HTML pages providing a mockup of the pages in the system.

Milestone 1 was managed using [M1](https://github.com/orgs/uhm-studymax/projects/1)
<img src="doc/M1.png" alt="Landing Page Screenshot">

## Milestone 2:
The goal of Milestone 2 was to implement the data model: the underlying set of Mongo Collections and the operations upon them that would support the BowFolio application.

Milestone 2 was managed using [M2](https://github.com/orgs/uhm-studymax/projects/4/views/1)
<img src="doc/M2final.png" alt="Landing Page Screenshot">
   
## Milestone 3:
The goal of Milestone 3 was to clean up the code base and fix minor UI issues.

Milestone 3 was managed using [M3]([https://github.com/orgs/uhm-studymax/projects/1](https://github.com/orgs/uhm-studymax/projects/7/views/1?pane=issue&itemId=89428064&issue=uhm-studymax%7Cuhm-studymax.github.io%7C18))
<img src="doc/M3Start.png" alt="Landing Page Screenshot">



## Deployment:
Current live [link](https://study-buddy-inky-nine.vercel.app/) for the project

